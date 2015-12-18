HTML Guide
=====


- - -

###CCIC WACN WEB Front End Development Team Code Standard Document###

_Author: Jason Zhang_
_Email: [v-zhlong@microsoft.com](mailto:v-zhlong@microsoft.com)_
_Last update: 2015-12-17_

- - -

## Document Directory

1. [Code Style](#codeStyle)
2. [Attribute](#attribute)
3. [Tag](#tag)
4. [Head Setting](#headSetting)
5. [Image](#image)
6. [Form](#6)
7. [Comments](#7)

<a name="codeStyle"></a>
## 1 Code Style

### 1.1 Code Indentation
**[强制]** 使用**4**个空格作为一个缩进层级，不允许使用**2**个空格或者**tab**字符。

<a name="attribute"></a>
## 2 Attribute
### 2.1 Attribute Quotes
**[强制]** 属性值使用**双引号**，不允许使用单引号，不允许不使用引号；

示例：

```xml
<!-- Better -->
<a href="/" title="Windows Azure">Windows Azure</a>
```

### 2.2 属性大小写
**[强制]** 属性名统一使用**小写**，不允许大小写混合。

### 2.3 属性布尔值
**[建议]** 布尔类型的属性，建议不添加属性值，至少同一项目要保持一致；

示例：

```xml
<!-- Better -->
<input type="text" disabled>
<input type="checkbox" checked>
```

### 2.4 属性声明顺序
**[建议]** HTML属性声明顺序尽量按照以下顺序依次排列，确保代码的易读性。

* `class`
* `id`, `name`
* `data-*`
* `src`, `for`, `type`, `href`
* `title`, `alt`
* `aria-*`, `role`

示例：

```xml

```

**[[Top]](#)**

<a name="tag"></a>
## 3 Tag


**[[Top]](#)**

<a name="headSetting"></a>
## 4 Head Setting


**[[Top]](#)**

<a name="image"></a>
## 5 Image


**[[Top]](#)**

<a name="form"></a>
## 6 Form


**[[Top]](#)**

<a name="comments"></a>
## 7 Comments


**[[Top]](#)**