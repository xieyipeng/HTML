# HTML(超文本标记语言)

[教程链接](http://www.runoob.com/html/html-tutorial.html)

查看完整的HTML属性列表: [HTML 标签参考手册](http://www.runoob.com/tags/html-reference.html)。

[速查列表](http://www.runoob.com/html/html-quicklist.html)

#### 解析

- **<!DOCTYPE html>** 声明为 HTML5 文档
- **<html>** 元素是 HTML 页面的根元素
- **<head>** 元素包含了文档的元（meta）数据，如 <meta charset="utf-8"> 定义网页编码格式为 **utf-8**。
- **<title>** 元素描述了文档的标题
- **<body>** 元素包含了可见的页面内容
- **<h1>** 元素定义一个大标题
- **<p>** 元素定义一个段落

#### 通用声明

**HTML5**

`<!DOCTYPE html>`

**HTML 4.01**

`<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN"`

`"http://www.w3.org/TR/html4/loose.dtd">`

**XHTML 1.0**

`<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN"`

`"http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">`

查看完整网页声明类型 [DOCTYPE 参考手册](http://www.runoob.com/tags/tag-doctype.html)。

#### 4个实例

* **html标题**

  <h1>这是一个标题</h1>

  <h2>这是一个标题</h2>

  <h3>这是一个标题</h3>

* **html段落**

  <p>这是一个段落</p>

  <p>这是一个段落</p>

* **html链接**

  <a href="链接地址">这是一个链接</a>

* **html图像**

  <img src="图片地址" width="258" height="39"/>

> <body> 元素定义了 HTML 文档的主体。 

#### 属性参考手册

查看完整的HTML属性列表: [HTML 标签参考手册](http://www.runoob.com/tags/html-reference.html)。

下面列出了适用于大多数 HTML 元素的属性：

| 属性  | 描述                                                         |
| ----- | ------------------------------------------------------------ |
| class | 为html元素定义一个或多个类名（classname）(类名从样式文件引入) |
| id    | 定义元素的唯一id                                             |
| style | 规定元素的行内样式（inline style）                           |
| title | 描述了元素的额外信息 (作为工具条使用)                        |

#### html标题

> 请确保将 HTML 标题 标签只用于标题。不要仅仅是为了生成**粗体**或**大号**的文本而使用标题。
>
> 搜索引擎使用标题为您的网页的结构和内容编制索引。
>
> 因为用户可以通过标题来快速浏览您的网页，所以用标题来呈现文档结构是很重要的。
>
> 应该将 h1 用作主标题（最重要的），其后是 h2（次重要的），再其次是 h3，以此类推。

#### HTML水平线

<hr> 标签在 HTML 页面中创建水平线。  

#### 换行操作

| 标签 | 描述                 |
| ---- | -------------------- |
| <p>  | 定义一个段落         |
| <br> | 插入单个折行（换行） |

#### 格式化标签

| [<b>](http://www.runoob.com/tags/tag-b.html)            | 定义粗体文本 |
| ------------------------------------------------------- | ------------ |
| [<em>](http://www.runoob.com/tags/tag-em.html)          | 定义着重文字 |
| [<i>](http://www.runoob.com/tags/tag-i.html)            | 定义斜体字   |
| [<small>](http://www.runoob.com/tags/tag-small.html)    | 定义小号字   |
| [<strong>](http://www.runoob.com/tags/tag-strong.html)  | 定义加重语气 |
| [<sub>](http://www.runoob.com/tags/tag-sub.html)        | 定义下标字   |
| [<sup>](http://www.runoob.com/html/m/tags/tag-sup.html) | 定义上标字   |
| [<ins>](http://www.runoob.com/tags/tag-ins.html)        | 定义插入字   |
| [<del>](http://www.runoob.com/tags/tag-del.html)        | 定义删除字   |

#### 链接标签

| 标签                                         | 描述             |
| -------------------------------------------- | ---------------- |
| [<a>](http://www.runoob.com/tags/tag-a.html) | 定义一个超级链接 |

#### head

[<title> - 定义了HTML文档的标题](http://www.runoob.com/try/try.php?filename=tryhtml_title)
使用 <title> 标签定义HTML文档的标题

[<base>- 定义了所有链接的URL](http://www.runoob.com/try/try.php?filename=tryhtml_base)
使用 <base> 定义页面中所有链接默认的链接目标地址。

[<meta> - 提供了HTML文档的meta标记](http://www.runoob.com/try/try.php?filename=tryhtml_meta)
使用 <meta> 元素来描述HTML文档的描述，关键词，作者，字符集等。

<head> 元素包含了所有的头部标签元素。在 <head>元素中你可以插入脚本（scripts）, 样式文件（CSS），及各种meta信息。

可以添加在头部区域的元素标签为: <title>, <style>, <meta>, <link>, <script>, <noscript>, and <base>.

## 内部样式表

当单个文件需要特别样式时，就可以使用内部样式表。你可以在<head> 部分通过 <style>标签定义内部样式表:

<head>
<style type="text/css">
body {background-color:yellow;}
p {color:blue;}
</style>
</head>

 

------

## 外部样式表

当样式需要被应用到很多页面的时候，外部样式表将是理想的选择。使用外部样式表，你就可以通过更改一个文件来改变整个站点的外观。

<head>
<link rel="stylesheet" type="text/css" href="mystyle.css">
</head>

## HTML <div> 元素

HTML <div> 元素是块级元素，它可用于组合其他 HTML 元素的容器。

<div> 元素没有特定的含义。除此之外，由于它属于块级元素，浏览器会在其前后显示折行。

如果与 CSS 一同使用，<div> 元素可用于对大的内容块设置样式属性。

<div> 元素的另一个常见的用途是文档布局。它取代了使用表格定义布局的老式方法。使用 <table> 元素进行文档布局不是表格的正确用法。<table> 元素的作用是显示表格化的数据。

## HTML <span> 元素

HTML <span> 元素是内联元素，可用作文本的容器

<span> 元素也没有特定的含义。

当与 CSS 一同使用时，<span> 元素可用于为部分文本设置样式属性。











