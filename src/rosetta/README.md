# Rosetta IME
Enhance the Chinese input experience in Xiaomi Vela.

## Features

 - 多种输入方式支持
 - 基于输入频次的个人热点词库
 - 允许接入自部署云端联想API
 - Material风格设计
 - 功能强大, 操作便捷


## 组件props

### show
类型：Boolean
默认值：false
描述：是否显示输入法

### method
类型：String
默认值：chn_9_pinyin
描述：输入方法

#### 输入方法ID对照表
| 输入法名称       | 输入法ID         |
|----------------|----------------|
| 拼音九键       | chn_9_pinyin   |
| 拼音26键 | chn_26_pinyin  |
| 英文26键 | eng_26_qwerty  |
| 数字符号 | num_signs      |

#### 