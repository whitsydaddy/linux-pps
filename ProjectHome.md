集合了Fedora和Ubuntu PPStream安装。

【Fedora系统的安装】
软件版本：1.0
  * 安装需求：Fedora13-live/Fedora14-live, 只能用于x86 Linux个人电脑.
  * 软件大小：1.4MB(tar.gz包)

安装说明:
软件下载：http://code.google.com/p/linux-pps/downloads/list


安装PPS:
  * 所有的支持包都已在shell安装脚本中。
  * 推荐使用ppstream\_1.0\_i386.tar.gz安装:
  * 【xxx@localhost~】$su
  * 密码：输入root用户密码
  * 【root@localhost xxx】#cd 下载
  * 【root@localhost 下载】#tar xvfz ppstream\_1.0\_i386.tar.gz
  * 【root@localhost 下载】#cd ppstream
  * 【root@localhost ppstream】#sh install.sh
脚本会自动安装支持包和ppstream

注：如果出现观看没有声音
请打开PPS操作“工具”---“选项”---“选择音频设备”---“设置当前音频设备”为“alsa”

可选安装：
  * MPlayer视频解码器: MPlayer Essential Codec Pack(http://www.mplayerhq.hu/MPlayer/releases/codecs/essential-20071007.tar.bz2)

卸载PPS：
  * 【root@localhost ppstream】#sh uninstall.sh

软件已在Fedora13-live和Fedora14-live测试OK
本软件包参考pps-Ubuntu版和网络中的一些资料，希望得到大家的支持！

【Ubuntu系统的安装】
软件版本：0.1.1678

PPS Ubuntu PC版本使用说明来自:http://dl.pps.tv

发表时间:2010-11-04


  * 安装需求：Ubuntu 8.04+, 只能用于x86 Linux个人电脑.
  * 软件大小：1.5MB(deb包)

安装说明:

辅助软件:
> 安装PPS Linux版本前需要先安装以下辅助软件:
  * QT库, 4.4.0及以上版本
  * libFuse库, 2.7.2及以上版本
  * Mplayer, 1.0rc2及以上版本
  * MPlayer视频解码器: MPlayer Essential Codec Pack(http://www.mplayerhq.hu/MPlayer/releases/codecs/essential-20071007.tar.bz2)

> 推荐使用apt-get方式安装: sudo apt-get install libqt4-core libqt4-dbus libqt4-gui libqt4-network libqt4-webkit libqt4-xml libfuse2 mplayer

安装PPS:
> sudo dpkg -i ppstream\_1.0.0-1\_i386.deb