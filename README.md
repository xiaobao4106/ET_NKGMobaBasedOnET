# NKGNMobaBasedOnET

#### 介绍
基于ET框架的Moba游戏，本着学习的原则，所以本仓库可能会为了添加元素而添加元素，见谅。

如果你对这个开源项目有好的想法或者想和大家一起交流，可以提Issues或者加QQ群：959572557

对于想系统学习本项目而无从下手的，推荐去看看本项目的Wiki，里面有运行指南和基础教程以及相关技术点讲解。
[这是Wiki地址](https://gitee.com/NKG_admin/MKGMobaBasedOnET/wikis)

本项目中所有的插件仅供学习交流使用，请务必支持正版！

最后，大家一起加油！   :neckbeard:  :neckbeard:  :neckbeard: 

### 作者有话说

很抱歉，我要开始佛性维护这个项目了，因为我要开始忙于学业和准备春招，鱼和熊掌不可得兼（主要是我现在游戏上瘾每天还要打几小时游戏），现在的Demo包含了完整的战斗系统架构，大家可以参考，很多地方还很粗糙，但是代码我觉得还是很好懂得，祝大家学习进步！

#### 已实现功能列表

- 整合FairyGUI 2019.4.27
- 丰富AB编辑器接口，专门为FairyGUI增加了AB标签工具   2019.4.27
- 资源的下载更新界面和逻辑开发完成   2019.4.28
- 登录注册，接入MongoDB数据库  2019.5.1
- 游戏大厅UI，账号之间冲突处理，心跳开发  2019.5.6
- 人物同步，自动寻路（包含点击小地图寻路）2019.5.11
- 整合可视化结点编辑器（配置树状数据） 2019.5.19
- 将人物和技能数据转移到服务端并解析  2019.5.27
- 整合Box2D作为服务端碰撞方案  2019.6.10
- 提取LOL资源作为项目主要资源 2019.6.20
- 整合行为树到客户端和服务端，将配合技能编辑器制作技能系统 2019.6.25
- 新增贴图（dds）工作流，提高开发效率  2019.7.2
- 选定状态同步为游戏同步策略，初步实现多玩家动画同步工作 2019.7.3
- 完成Box2D可视化编辑器的制作  2019.7.19
- 重构可视化结点编辑器代码，将用它做更多的事情 2019.7.24
- 完成碰撞关系可视化编辑器的制作，附带自动生成代码功能 2019.8.1
- 完成服务端Box2D相关架构的搭建 2019.8.14
- 移除传统行为树，完成NPBehave行为树可视化编辑器制作(dev分支) 2019.8.26
- 基本实现基于NPBehave的可视化技能系统编辑器 2019.9.28
- 基于NPBehave的技能系统完成，附诺克Q技能完整流程Demo 2019.10.3 

#### 开发计划

1. 使用Shader实现人物在河道行走时的水波纹效果
2. 使用Shader实现人物描边效果

#### 开发进度展示


![输入图片说明](https://gitee.com/uploads/images/2019/0502/173207_17e8e767_2253805.png "资源更新界面")
![输入图片说明](https://gitee.com/uploads/images/2019/0502/173246_f83a8591_2253805.png "登录注册界面")
![输入图片说明](https://gitee.com/uploads/images/2019/0502/173252_7dbcd604_2253805.png "游戏大厅界面")
![输入图片说明](https://images.gitee.com/uploads/images/2019/0630/130133_d3559984_2253805.png "战斗界面第二版")
![输入图片说明](https://images.gitee.com/uploads/images/2019/0720/185840_f28e17e6_2253805.jpeg "Box2D编辑器界面")
![输入图片说明](https://images.gitee.com/uploads/images/2019/1003/160635_1de5993c_2253805.png "诺克Q技能行为树示例")
![输入图片说明](https://images.gitee.com/uploads/images/2019/0919/163758_138e22e9_2253805.png "技能系统架构.png")