# common-unix-linux-command

常用unix/linux命令

```bash

// 测试某个端口是否开放
nc -vz -w 2 10.211.55.20 22

// 输出结果
Connection to 10.211.55.20 port 22 [tcp/ssh] succeeded!

```

CentOS7 常用
```
1.查看防火墙状态 firewall-cmd --state

2.启动防火墙 systemctl start firewalld.service

3.开放端口 firewall-cmd --zone=public --add-port=8080/tcp --permanent

4.重启防火墙 systemctl restart firewalld.service

5.重新加载配置 firewall-cmd --reload


————————————————
版权声明：本文为CSDN博主「EricaKang」的原创文章，遵循 CC 4.0 BY-SA 版权协议，转载请附上原文出处链接及本声明。
原文链接：https://blog.csdn.net/happybruce8023/java/article/details/87965812
```
