# Blender_3渲2预设
## 声明
~~本项目仅是```Blender_3渲2预设```的更新日志和使用注意事项，文件下载请到我的[模之屋主页](https://www.aplaybox.com/u/622277086)  
下载密码在b站的视频简介~~  
所有预设文件本人已经clone到本项目，并且没有密码(以后也没有)
## 2024/8/9追加
本人预感到模之屋可能会出事，所以把文件搬过来了  
## 使用注意事项
**禁止用于除创作激励、直播以外的商业性用途  
禁止二次配布  
禁止用于18禁作品，极端宗教宣传，血腥恐怖猎奇作品，人身攻击等  
他人使用本预设所造成的一切不良后果，不由作者本人承担，请向使用者追究全部责任  
使用请标明作者```氧度菌```**
## 更新日志
### V3.1
[B站视频](https://www.bilibili.com/video/BV1PkhheeEzu/)
1. 从原来的```MMD_Blender渲染预设```改名为```Blender3渲2预设``` (继承版本号)
2. 节点更新

    着色器节点
    + 解决着色器节点在特定条件下材质过曝的问题
    + 移除```阴影SDF```节点组的```ilm贴图```节点
    + 移除```阴影SDF```与```皮肤SDF```节点组的```漫射光```节点
    + ```面部阴影SDF```与```面部阴影_矢量```列入弃用名单

    几何节点
    + 新增```球体阴影```节点组
    + ```灯光```节点组改名为```日光阴影```
    + ```面部矢量```与```灯光矢量```节点列入弃用名单
    + 对节点组进行了整理打组  
### V2.1
[B站视频](https://www.bilibili.com/video/BV1Rj421S7eK/)
1. 移除了```卡通、球体材质的支持```
2. 移除了```阴影SDF```的```金属度法线```,```金属亮度```(合并到自发光强度)
3. 移除了皮肤相关节点的```亮面暗面调整```,```皮肤颜色系数```
4. 调整了一些默认参数
5. 简化了主要节点  
## V2.0
[B站视频](https://www.bilibili.com/video/BV154421F7ex/)
1. 新增对ilm贴图的支持
2. 新增对cycles的支持(有一点bug)
3. 修复了一些bug
4. ~~出现了更多bug~~
5. 移除了HIM  
### V1.0
[B站视频](https://www.bilibili.com/video/BV1Ne41127sj/)
特点:阴影使用Shader->RGB+颜色渐变 不需要光照贴图 不过BUG也很多
后面会加上ilm贴图的支持