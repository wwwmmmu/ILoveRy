# 关于第三方设备登录少年派

## 方法一

>若你的手机已经**Root**，且安卓系统为**8.0**及以上，你可以继续食用接下来的教程

>若你不符合两个条件其中任何一个，则请前往[方法二](#方法二)

>我们马上开始

### **需要准备的工具**

<details markdown='1'><summary>展开/收起</summary>


- [ ] 已经获取**Root**权限的手机

- [x] [**Myipad_Plugin.apk**](https://github.com/Shelterforyou/ILoveRy/raw/main/Applications/MyiPad%20Plugin_0.2.apk)

- [x] [**Lsposed.apk**](https://github.com/Shelterforyou/ILoveRy/raw/main/Applications/LSPosed_v1.5.2.apk)

- [x] [**Magisk_23.0.apk**](https://github.com/Shelterforyou/ILoveRy/raw/main/Applications/Magisk_23.0.apk)

- [x] [**Riru-v26.1.3.r513.8e95115fd4(513).zip**](https://github.com/Shelterforyou/ILoveRy/raw/main/Zips/%20riru-v26.1.3.r513.8e95115fd4(513).zip)

- [x] [**Riru_-_LSPosed-v1.6.2_(6152)(6152).zip**](https://github.com/Shelterforyou/ILoveRy/raw/main/Zips/%20riru_-_lsposed-v1.6.2_(6152)(6152).zip)

</details>

>首先在手机上安装**Myipad_5.2.352411.apk**，**Magisk_23.0.apk**，**Myipad_Plugin.apk**和
>**Lsposed.apk**

>打开**Magisk_23.0.apk**，等待一会后若提示修复运行环境，则根据提示重启即可

>右下角四个按钮中，点击最右边的那个

>选择**从本地安装**，找到并打开刚刚下载的两个压缩文件

>先刷入**Riru-v26.1.3.r513.8e95115fd4(513).zip**，忽略右下角的**重启**，重复上述步骤，从本地安装

>接着刷入**Riru_-_LSPosed-v1.6.2_(6152)(6152).zip**，刷入完毕后，点击右下角**重启**

>重启后，打开**Lsposed.apk**，若出现绿色的**已激活**，则说明你已经成功刷入**Lsp**

>点击**模块**，点击**Myipad_Plugin**，选中**少年派**

>然后重启手机

>此时打开**少年派**了，并在弹出的窗口中**只选中第一个**:**fake Hardware**，然后你就可以绕过**硬件认证**，成功在第三方设备登录**少年派**了

>大功告成!!

## 方法二

>若你的手机没有获取**Root**权限或者安卓版本低于**8.0**，则你可以使用如下方法

>建议使用低版本登录，高版本可能会存在诸多**Bug**

>我们马上开始

### **需要准备的工具**

<details markdown='1'><summary>展开/收起</summary>


- [ ] 未获取**Root**权限的手机

- [x] **Myipad_Plugin.apk**

- [x] **VirtualXposed_0.18.2_target-sdk-21.apk**

- [x] **Myipad_5.2.352411.apk**

- [x] [点击下载所有内容](https://wwd.lanzoui.com/b02ckrsyj)

</details>

>首先在手机上安装所提供的所以软件

>打开**VirtualXposed_0.18.2_target-sdk-21.apk**，点击**菜单**(屏幕下方的圆形)

>点击添加应用，选择 **Myipad_5.2.352411.apk**和**Myipad_Plugin.apk**

>安装完成后，打开**VXP**中的**Xposed installer**

>点击**模块**，勾上**Plugin**

>然后再次进入**菜单**，点击最后一项**重启**，等待

>此时在**VXP**中打开**少年派**，并在弹出的窗口中**只选中第一个**:**fake Hardware**，然后你就可以绕过**硬件认证**，成功在第三方设备登录**少年派**了

>如果出现**插件**使用问题，请前往[此处](https://tieba.baidu.com/p/7561863919)参考相关内容

>大功告成!!
