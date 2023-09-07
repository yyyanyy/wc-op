[![若部分图片无法正常显示，请挂上机场浏览或点这里到末尾看修复教程](https://visitor-badge.glitch.me/badge?page_id=sirpdboy-visitor-badge)](#解决-github-网页上图片显示失败的问题) [![](https://img.shields.io/badge/TG群-点击加入-FFFFFF.svg)](https://t.me/joinchat/AAAAAEpRF88NfOK5vBXGBQ)

[myautocore 加强版预览信息OPENWRT专用](https://github.com/sirpdboy/myautocore)
======================
请 **认真阅读完毕** 本页面，本页面包含注意事项和如何使用。

## 功能说明：

###  自动挂载自动分区和格式化功 来源LEAN大的  autocore 脚本。

###  本着人人为我，我为人人的原则，增加温度，类型，网卡MAC，时间等更多详细内容显示。不敢独享，特分享出来，为OPENWRT添砖加瓦。

<img src="doc/1.jpg" >
<img src="doc/2.jpg" >
## 编译使用方法 [![](https://img.shields.io/badge/-编译使用方法-F5F5F5.svg)](#编译使用方法-)


### 将automount添加至 LEDE/OpenWRT 源码的方法。

### 下载源码方法：

##由于习惯问题，会和LEAN大中的autocore冲突 ，建议编译前先删除：rm -rf package/lean/autocore

 ```Brach
 
    # 下载源码

    git clone https://github.com/sirpdboy/myautocore package/myautocore
	
    make menuconfig
	
 ``` 
 
### 配置菜单

 ```Brach
 
    make menuconfig
	
	# 找到 LuCI -> Applications, 选择 myautocore, 保存后退出。
	
 ``` 
### 编译

 ```Brach 
 
    # 编译固件
	
    make package/myautocore/compile V=s
 ```

## 说明 [![](https://img.shields.io/badge/-说明-F5F5F5.svg)](#说明-)

源码来源：https://github.com/sirpdboy/myautocore

你可以随意使用其中的源码，但请注明出处。

============================



## 使用与授权相关说明
 
- 本人开源的所有源码，任何引用需注明本处出处，如需修改二次发布必告之本人，未经许可不得做于任何商用用途。


# My other project

- 网络速度测试 ：https://github.com/sirpdboy/NetSpeedTest

- 定时设置插件 : https://github.com/sirpdboy/luci-app-autotimeset

- 关机功能插件 : https://github.com/sirpdboy/luci-app-poweroffdevice

- opentopd主题 : https://github.com/sirpdboy/luci-theme-opentopd

- kucat 主题: https://github.com/sirpdboy/luci-theme-kucat

- 家长控制: https://github.com/sirpdboy/luci-theme-parentcontrol

- 系统高级设置 : https://github.com/sirpdboy/luci-app-advanced

- ddns-go动态域名: https://github.com/sirpdboy/luci-app-ddns-go

- 进阶设置（系统高级设置+主题设置kucat/agron/opentopd）: https://github.com/sirpdboy/luci-app-advancedplus

- 设置向导: https://github.com/sirpdboy/luci-app-wizard

- 分区扩容: https://github.com/sirpdboy/luci-app-partexp

- lukcy大吉: https://github.com/sirpdboy/luci-app-lukcy

## 捐助

![screenshots](https://raw.githubusercontent.com/sirpdboy/openwrt/master/doc/说明3.jpg)

|     <img src="https://img.shields.io/badge/-支付宝-F5F5F5.svg" href="#赞助支持本项目-" height="25" alt="图飞了😂"/>  |  <img src="https://img.shields.io/badge/-微信-F5F5F5.svg" height="25" alt="图飞了😂" href="#赞助支持本项目-"/>  | 
| :-----------------: | :-------------: |
|![xm1](https://raw.githubusercontent.com/sirpdboy/openwrt/master/doc/支付宝.png) | ![xm1](https://raw.githubusercontent.com/sirpdboy/openwrt/master/doc/微信.png) |

<a href="#readme">
    <img src="https://img.shields.io/badge/-返回顶部-orange.svg" alt="图飞了😂" title="返回顶部" align="right"/>
</a>
