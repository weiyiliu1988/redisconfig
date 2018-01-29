# Redis Linux install

1. yum install redis
2. redis.conf port确认（密码requirepass 更改
3. redis开机启动脚本-》/etc/init.d/下
4. chmod 777 脚本文件 赋予可执行权限
5. 启动 redis 服务
6. redis-cli测试 （set,get)
8. chkconfig redis on
9. reboot 重启系统验证是否自启动
