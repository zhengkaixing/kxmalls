> kxmalls外卖生鲜多商户，针对中小商户、企业和个人学习者开发。使用Java编码，采用SpringBoot、Mybatis-Plus等易用框架，适合个人学习研究。同时支持单机部署、集群部署，用户与店铺范围动态定位，中小商户企业可根据业务动态扩容。kxmalls使用uniapp前端框架，可同时编译到 微信小程序、H5、Android App、iOS App等几个平台，可为中小商户企业节约大量维护成本。也可支撑中小商户企业前期平台横扩需求。


---
QQ讨论群：587493946 (进群前，请在网页右上角点star)

#### 数据库初始化sql文件，请进入讨论交流群，群文件自行下载，欢迎讨论与交流
---
#### 优先更新地址

kxmall项目结构:

- Java 后端服务
    - 目前只开源后端代码，需要前端功能代码，进QQ讨论群（587493946）联系群主。
    - kxmalls-admin: 启动器-提供管理员管理系统的WebApi（专门用于后端管理请求地址，打一个包）
    - kxmalls-portal: 启动器-提供APP、小程序、H5与骑手APP、小程序、H5用户请求的WebApi（专门用于app管理请求地址，打一个包）
    - kxmalls-core: 提供注解、核心代码、工具类等
    - kxmalls-pay: 支付模块

    
- Vue 前端页面
    - 目前只开源后端代码，需要前端功能代码，进QQ讨论群（587493946）联系群主。
    - kxmalls-admin-ui: 基于element-ui的后台管理页面
    - kxmalls-app-ui: 基于uniapp的小程序、H5、APP前端代码
    - kxmalls-rider-ui: 基于uniapp的小程序、H5、APP骑手代码
  
- sql: 数据库初始化SQL脚本

* 阿里云折扣场：[点我进入](https://www.aliyun.com/minisite/goods?userCode=gclm7a7u)&nbsp;&nbsp;
* 腾讯云秒杀场：[点我进入](https://url.cn/G0fq6Mm5)&nbsp;&nbsp;

#### 数据库初始化sql文件，请进入讨论交流群，群文件自行下载，欢迎讨论与交流
---
#### 优先更新地址

[01-kxmalls源码地址](https://gitee.com/zhengkaixing/kxmalls.git) https://gitee.com/zhengkaixing/kxmalls.git

---

#### 用户端系统演示

下面是微信小程序真机模式调试的界面，可Android安装Apk,也可同时支持苹果。
在这基础上，还增加了H5。可内置到微信公众号上，变成公众号商城！尽情体验！


---
- H5客户端（可打包成小程序、APP）
  - 演示地址: [https://h5.kxmalls.vip/](https://h5.kxmalls.vip/)
  - 登录名:16666666666 密码:123456 （访问请打开浏览器F12开发模式,使用手机模式进行操作）
  - 使用余额支付即可，可正常体验操作流程
- 微信小程序-体验（可打包成小程序、APP）
    - 已跳过支付模块，可正常体验操作流程（注意：需要自己手动获取一下定位，方可正常使用。）
    - ![河禾生鲜](https://kxmalls.oss-cn-hangzhou.aliyuncs.com/kxmalls-kh.jpg)    
- Pages

| kxmalls客户端 | kxmalls客户端 | kxmalls客户端 |
| :----: | :----: | :----: |
| ![kxmalls生鲜](https://kxmalls.oss-cn-hangzhou.aliyuncs.com/kxmalls1.png) | ![kxmalls生鲜](https://kxmalls.oss-cn-hangzhou.aliyuncs.com/kxmalls7.jpg) | ![kxmalls生鲜](https://kxmalls.oss-cn-hangzhou.aliyuncs.com/kxmalls6.jpg)

| 订单打印 | 商家订单推送 | 骑手订单推送  |
| :----: | :----: | :----: |
| ![订单打印](https://kxmalls.oss-cn-hangzhou.aliyuncs.com/kxmall-print.jpg) | ![订单推送](https://kxmalls.oss-cn-hangzhou.aliyuncs.com/kxmalls10.jpg) |  ![订单推送](https://kxmalls.oss-cn-hangzhou.aliyuncs.com/kxmalls9.jpg) 
#### 后台端系统演示

使用免费开源框架vue-element-admin，基于element-ui的后台管理页面！尽情体验！


---
- Admin后台
  - 演示地址: [http://www.kxmalls.vip/#/login](http://www.kxmalls.vip/#/login)
  - 商家账号:小黑水果生鲜 密码:123456
  - 登录名(超级管理员):admin (需要体验的，密码可以关注公众号，回复:3)
  - ![河禾生鲜](https://nontax.oss-cn-beijing.aliyuncs.com/kxmall/PublicQr.jpg)
- Pages
 
![kxmalls生鲜](https://kxmalls.oss-cn-hangzhou.aliyuncs.com/kxmalls3.png)  
![kxmalls生鲜](https://kxmalls.oss-cn-hangzhou.aliyuncs.com/kxmalls4.png)   


#### 骑手端系统演示

---
- h5骑手后台（可打包成小程序、APP）
  - 演示地址: [https://rider.kxmalls.vip/](https://rider.kxmalls.vip/)
  - 登录名:13333333333 验证码:123456 （访问请打开浏览器F12开发模式,使用手机模式进行操作）
- 微信小程序-体验（可打包成小程序、APP）
    - 微信一键登录（注意：需要进入管理后台进行审核，方可正常使用。）
    - ![河禾生鲜](https://kxmalls.oss-cn-hangzhou.aliyuncs.com/kxmalls-rider.jpg)    
- Pages

| kxmalls生鲜 | kxmalls生鲜 |
| :----: |  :----: | 
| ![kxmalls生鲜](https://kxmalls.oss-cn-hangzhou.aliyuncs.com/kxmalls2.png)   | ![kxmalls生鲜](https://kxmalls.oss-cn-hangzhou.aliyuncs.com/kxmalls8.jpg)   |


#### 项目部署方式

>项目部署
##### ⓪ 服务器推荐
服务器可根据自身业务来选购，单机环境推荐2C4G
* 阿里云折扣场：[点我进入](https://www.aliyun.com/minisite/goods?userCode=gclm7a7u)&nbsp;&nbsp;
* 腾讯云秒杀场：[点我进入](https://curl.qcloud.com/XslPhodG)&nbsp;&nbsp;

##### ① 基础运行环境

| 运行环境 | 版本号 |
|:--------|:--------|
|  MySQL   |  5.7（推荐）   |
|  JDK   |  1.8（推荐）   |
|  Redis   |  4.0.1（其他也可以）   |
|  Nginx  |  只要Web容器就可以了  |

Redis安装可直接使用yum安装 
	
	yum install redis

安装完成后使用 redis-cli 命令，若能进入，则表示redis安装完成

1.服务器安装必备软件[JDK | mysql | Redis | Nginx]

#### 版权声明

本项目后端由云伴工作室开发，禁止未经授权用于商业用途。目前只开源后端代码（kxmalls-java）与后端管理代码（kxmalls-admin-ui），进QQ讨论群（587493946）联系群主。


### SaaS服务

正在研发中...
