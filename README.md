# 项目实战 —— 飞机大战

## 目标

* 强化 **面向对象** 程序设计
* 体验使用 `pygame` 模块进行 **游戏开发**

## 实战步骤

1. `pygame` 快速体验
    * 此项目中的`Pro_01_Pygame入门---Pro_12_演练精灵`等12个Python文件均为`pygame`的极速体验部分，主要包括以下几部分内容：
        * 使用`pygame`创建图形窗口
        * 理解**图像**并且实现图像绘制
        * 理解**游戏循环**和**游戏时钟**
        * 理解**精灵**和**精灵组** 
2. **飞机大战** 实战
    * 此项目中的`plane_main.py`与`plane_sprites.py`两个文件为**飞机大战**部分的源代码，主要包括以下几个方面的内容：
        * 游戏框架搭建
        * 游戏背景
        * 敌机出场
        * 英雄出场
        * 碰撞检测

## 确认模块 —— pygame

* `pygame` 就是一个 Python第三方模块，专为电子游戏所设计
* 官方网站：https://www.pygame.org/

| 网站栏目 | 内容 |
| --- | --- |
| `GettingStarted` | 在各平台安装模块的说明 |
| `Docs` | `pygame` 模块所有 **类** 和 **子类** 的参考手册 |

### 安装 pygame

```bash
$ sudo pip3 install pygame
```

### 验证安装

```bash
$ python3 -m pygame.examples.aliens
```
### 运行

```bash
$ python3 plane_main.py
```

**Note**:
* 此项目的所有详细`markdown`文档(记录整个项目的开发过程)在`document`目录下面，如有需要，请自行查看
* 如果对于此项目的代码有任何问题，欢迎与本人联系，可在此仓库提交`Issues`即可

### 参考

本项目参考自<b>《传智播客》Python基础班项目实战</b>，在此表示感谢