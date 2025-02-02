# 🧸 棉花糖幻兽帕鲁开服器

[![访问官网](https://img.shields.io/badge/访问官网-简体中文-blue?style=for-the-badge)](https://mht-palworldserverkit.yankekeji.cn/zh_cn.html#/)
[![加入QQ群](https://img.shields.io/badge/加入QQ群-点击加入-green?style=for-the-badge)](https://qm.qq.com/cgi-bin/qm/qr?k=N_6IyZrxAur6vy8c_8t-3u3S53CjoX8A&jump_from=webapi&authKey=kJ2Ylbcr5OVpTQgGDn74ZFKTApiSx+wdyZ0ZlIP0gmv4+sG2LiPFdgPvUDwXvNH1)
[![访问B站](https://img.shields.io/badge/访问B站-官方空间-red?style=for-the-badge)](https://space.bilibili.com/681162160)
<br>
**棉花糖幻兽帕鲁开服器** 是由 **（中国）内蒙古研科科技有限公司** 开发的公益项目。该项目旨在为幻兽帕鲁（**PalWorld**）服务器提供快速搭建和在线管理功能。我们致力于让玩家和开发者更加便捷地使用本工具，并为社区做出贡献。

本项目完全免费，任何未经授权的售卖、复制、破解行为将会遭到法律追诉。我们坚决维护本项目的合法权益，保证用户在使用过程中获得纯粹的公益服务。

## 📋 支持的功能（Web Gui）
- （仪表盘）服务器状态监测（Palworld 服务端状态、Cpu占用率、内存占用率、在线玩家数、存档备份数、玩家在线记录图表、在线玩家所在区域图表）
- （安装/更新）一键式安装安装运行库（棉花糖亚太加速节点）、Palworld服务端（支持SteamCMD安装更新和棉花糖亚太加速节点安装更新）
- （配置/管理）一键可视化管理Palworld的配置文件、配置开服器支持的功能（玩家进入退出通知、禁止某些区域玩家进入、禁止Steam失信玩家进入、崩溃重启、优化服务端性能、设置社群服务器等）
- （玩家管理）一键查看玩家信息（Steam/Xbox、地理区域、封禁玩家、踢出玩家等）
- （反作弊）一键安装、更新、使用、配置公益反作弊项目（PalGurad）
- （定时任务）一键设置定时任务（每N分钟、每天）可以设置定时备份、定时开关重启Palworld服务端
- （备份管理）一键管理所有存档备份，下载、恢复存档备份

## 🖼️ 支持的功能（截图）
![仪表板](https://jdkj-asia-cdn-01.paonima.top/file/Mht_PalWorld_ServerKit/all_img/dashboard.png "仪表板截图")
![安装/更新](https://jdkj-asia-cdn-01.paonima.top/file/Mht_PalWorld_ServerKit/all_img/installAndUpdate.png "安装/更新截图")
![配置/管理](https://jdkj-asia-cdn-01.paonima.top/file/Mht_PalWorld_ServerKit/all_img/config.png "配置/管理截图")
![玩家管理](https://jdkj-asia-cdn-01.paonima.top/file/Mht_PalWorld_ServerKit/all_img/player.png "玩家管理截图")
![反作弊](https://jdkj-asia-cdn-01.paonima.top/file/Mht_PalWorld_ServerKit/all_img/antiCheat.png "反作弊截图")
![定时任务](https://jdkj-asia-cdn-01.paonima.top/file/Mht_PalWorld_ServerKit/all_img/autoTask.png "定时任务截图")
![备份管理](https://jdkj-asia-cdn-01.paonima.top/file/Mht_PalWorld_ServerKit/all_img/backup.png "备份管理截图")

## 🖥️ 运行环境

### Windows
- Windows 10
- Windows 11
- Windows Server 2016
- Windows Server 2019
- Windows Server 2022
- Windows Server 2025

### Linux
- 暂未支持，预计版本更新后会支持

## 🛠️ 运行库

- .NET 8.0

## 💾 硬件要求

- **硬盘**：>= 150MB （如果开启了备份存档，则需要更多空间）
- **带宽**：>= 1Mbps

## 📜 引用库申明

本项目引用了某些第三方库，我们尊重原第三方库的任何版权申明和协议，并要求用户也必须尊重。以下是本项目所使用的第三方库及其协议：

1. **Tabler**（MIT） 🧑‍💻
2. **Tabler Font ICON**（MIT） 📦  
   *我们向本项目赞助了 1 美金，以激励 Tabler 的开源公益*
3. **RestSharp**（Apache-2.0） 🔧
4. **Newtonsoft.Json**（MIT） 📝
5. **Microsoft.VisualBasic** [License](https://github.com/dotnet/corefx/blob/master/LICENSE.TXT) 💼
6. **Microsoft.Extensions.FileProviders.Embedded**（MIT） ⚙️
7. **Microsoft.Data.Sqlite**（MIT） 💻
8. **MaxMind.GeoIP2**（Apache-2.0） 🌍
9. **MaxMind.Db**（Apache-2.0） 🌐
10. **RconSharp**（MIT） 🎮
11. **Colorful.Console**（MIT） 🌈
12. **CliWrap**（MIT） 🔲
13. **Aria2.NET**（MIT） 📥
14. **SteamCMD API**（MIT） 💻
15. **Quartz**（Apache-2.0） 💼
16. **GeoCN**（GPL 3.0）🌍

本项目使用了 [GeoCN](https://github.com/ljxi/GeoCN) 库提供的离线 GeoIP 数据库（mmdb 文件）进行 IP 查询。该库的许可协议为 **GPL 3.0**。我们尊重该库的开源协议，若对库的使用、分发或修改有任何问题，请遵守 GPL 3.0 的相关条款。

我们不会修改 **GeoCN** 库本身，仅使用其提供的 **mmdb 数据库** 文件进行 IP 查询。对于该库的其他使用条款，请参考其 [GitHub 仓库](https://github.com/ljxi/GeoCN)。


## 📝 软著证书

申请中...

## ⚠️ 免责声明

本项目是一个公益项目，旨在为用户提供便捷的服务和工具。使用本项目时，您需要明确了解并同意以下条款：

1. **无任何形式的保证**：本项目提供的所有功能和服务“按现状”提供，且不作任何明示或暗示的保证，包括但不限于适销性、适合特定目的或非侵权的保证。
2. **不承担任何责任**：本项目的开发者和相关单位不对因使用本项目而产生的任何直接、间接、偶然、特殊、惩罚性或后果性的损害负责，尤其是因本项目的使用、功能缺失、服务中断、数据丢失或其他不可预见的情况带来的损失。
3. **用户自行承担风险**：在使用本项目时，用户需自行承担可能出现的风险和后果。任何因操作不当或未遵守相关规定所造成的损失，本项目不承担任何责任。
4. **遵守相关法律**：用户在使用本项目时应遵守当地法律法规，且不得用于任何非法目的或商业盈利目的。
5. **服务变更与中断**：本项目的开发者有权随时修改或暂停服务，且无需事先通知用户。对于因此带来的不便和损失，我们不承担任何责任。

我们建议用户在使用本项目前充分了解并接受上述免责声明条款。
