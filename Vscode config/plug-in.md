[toc]

### 界面美化 {ignore=false}
- vscode-icon
- background-cover
#### highlight-words
- 使用方法：
  - 您可以通过选择命令面板中的"Highlight Toggle Current"来添加单词，这将突出显示光标处或选择的单词。
  - 要停止突出显示，请选择"Highlight Remove"，然后选择所需的单词或表达式，或全部删除。
  - 您还可以通过"Highlight Remove All"命令删除所有突出显示的内容，而无需选择。
  - 要使用正则表达式进行突出显示，请选择"Highlight Expression"并输入表达式（斜杠可选），可以使用/表达式/i来忽略大小写（g标志是自动的，i标志被接受，其他标志被忽略）。
  - 要使用选项进行突出显示，请选择"Highlight Selection with Options"并在呈现时选择整个单词、忽略大小写或两者都选择。
  - 您可以通过"Set Highlight Mode"命令设置"Highlight Toggle Current"的模式。默认值可以在配置中设置。
  - 侧边栏可以在资源管理器视图中显示，并可以使用"Highlight Toggle Sidebar"命令进行切换。这提供了导航突出显示项、更改选项和删除的功能。
- 配置:
  - highlightwords.colors：这是一个轻/暗对的数组，用于各自的主题类型，您可以拥有尽可能少或尽可能多的颜色对。
  - highlightwords.box：如果为true，则将突出显示显示为选择周围的框，如果为false，则将突出显示设置为背景颜色。
  - highlightwords.defaultMode：初始化时的初始模式。0=默认，1=整个单词，2=忽略大小写，3=整个单词和忽略大小写。
  - highlightwords.showSidebar：在资源管理器窗口中提供了一个视图，用于搜索、更改选项和删除突出显示的内容。
```json
"highlightwords.colors": [
    { "light": "#b3d9ff", "dark": "cyan" },
    { "light": "#e6ffb3", "dark": "pink" },
    { "light": "#b3b3ff", "dark": "lightgreen" },
    { "light": "#ffd9b3", "dark": "magenta" },
    { "light": "#ffb3ff", "dark": "cornflowerblue" },
    { "light": "#b3ffb3", "dark": "orange" },
    { "light": "#ffff80", "dark": "green" },
    { "light": "#d1e0e0", "dark": "red" }                                        
    ...
],
"highlightwords.box": {
    "light": false,
    "dark": true
},
"highlightwords.defaultMode": {
    "default": 0
}

"highlightwords.showSidebar": {
    "default": true
}

```
- 快捷键配置
  - 先选择变量(光标放上去即可)，快捷键ctrl + shift+ p，然后输入highli…，然后选择Highlight Toggle Current，
  可以绑定快捷键ALT+B,方便高亮
  

### 第三方插件
- Draw.io Intergration
- STM32 VS Code Extension
- Keil Assistant

### 排版工具
- Markdown All in One
- LaTeX Utilities
- LaTeX Workshop
- Markdown Preview Enhanced

### 实用工具
- Git Graph
- Git History
- TONGYI Lingma
- Open



### [参考文档](https://blog.csdn.net/Dontla/article/details/131515569)
