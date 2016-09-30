# xcode使用技巧
**_该文档辅助自我记忆,当然最好练成不要鼠标操作的习惯，对编程效率提升有帮助_**
### 1. 常见快捷指令
    1.1 代码编写:
    command + /           注释命令
    ctrl    + i           自动对齐
    ctrl    + command + E 范围编辑，在当前文件批量修改代码


    1.2 查找与搜索
    command + 3           导航栏搜索
    ctrl    + 6           当前代码文件，快速搜索属性，函数，方法
    option  + command + O 快速文件和方法搜索
    command + f           文档内部搜索
    ctrl    + 1           打开'Show Related Items‘弹出菜单，并访问该方法的调用者

    1.3 界面切换与帮助信息
    option  + left        在辅助编辑器中打开文件
    option  + left        在变量、类、或者方法名上执行该操作来获得更多细节信息

    command + shift + j   大型项目中，导航栏定位当前文档位置
    control + cmd + 上/下  在.m文件和.h文件之间来回切换
    control + cmd + j     查看方法在头文件中的声明信息

    1.3 运行
    cmd + r               运行
    cmd + .               停止
    cmd + b               编译
    cmd + shift + b       静态内存分析编译，可以检查程序结构上是否存在内存泄露

### 2. 基本界面操作说明
**_只关注值得注意的界面操作，并慢慢补充_**

2.1 [xcode菜单选项详细探索](http://www.cocoachina.com/ios/20151204/14480.html) <br />
2.2 要点:
* 当多次重构工程造成代码没有错却编译失败时，可以尝试删除DerivedData目录。DerivedData目录是Xcode的编译缓存

### 3. 特别问题
3.1 [高效使用你的xcode](http://www.cocoachina.com/ios/20140731/9284.html)<br />
3.2 [有用插件](http://nshipster.com/xcode-plugins/)<br />
3.3 [注释使用](http://www.raywenderlich.com/66395/documenting-in-xcode-with-headerdoc-tutorial)<br />
3.4 VVDocument-Xcode规范注释生成器，CodePilot-全能搜索工具，ColorSense-Xcode颜色识别与预览插件（灰常不错），KSImageNamed-图片文件名自动补全并且能显示该图片的一个缩略图（灰常棒），XAlign-可以自定义对齐模式的常规代码对齐插件，cocoapods-第三方类库管理工具以及项目依赖管理神器（最值得推荐的神器）。作为一个ios 开发者，你应该需要知道这些。<br />
3.5 关于自定义代码块的使用，以及如何覆盖系统代码块方法。手熟，自学，无它而。<br />
3.6 辅助界面的使用<br />
3.7 调试注意<br />
3.8 代码部署<br />
3.9 应用商店上线<br />
