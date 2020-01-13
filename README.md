# Linux-NetSpeed
```
wget -N --no-check-certificate "https://raw.githubusercontent.com/chiakge/Linux-NetSpeed/master/tcp.sh"
chmod +x tcp.sh
./tcp.sh
```

不要随便在生产环境使用，生产环境建议手动安装   





脚本适用于：Debian 9+ / Ubuntu 18.04+ / Centos7+

一、BBR一键安装：

1、更换内核需要root权限，所以如果你是普通用户的话，需要root账号权限，如果你是root账号，那就忽略这个步骤：
sudo -i

2、BBR一键安装代码：
wget --no-check-certificate https://raw.githubusercontent.com/cx9208/Linux-NetSpeed/master/tcp.sh && chmod +x tcp.sh && ./tcp.sh

>>>若报错运行以下代码，不报错跳过：
yum -y install wget
rm -f /var/run/yum.pid

3、重新打开脚本，查看是否运行成功：
./tcp.sh
