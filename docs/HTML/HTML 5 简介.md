# 1. 第1章 HTML 5简介

## 1.1. HTML历史与HTML 5

**HTML**：Hyper Text Markup Language，超文本标记语言，是一种标记语言。

### 1.1.1. HTML 发展历史

* HTML(第1版)：1993年6月，互联网工作小组发布HTML工作草案；
* HTML 2.0：1995年11月作为 [RFC](https://en.wikipedia.org/wiki/Request_for_Comments) 1866 发布；
* HTML 3.2：1996年1月14日，[W3C组织](https://en.wikipedia.org/wiki/World_Wide_Web_Consortium) （World Wide Web Consortium）发布，第一个被广泛使用的HTML 标准；
* HTML 4.0：1997年12月18日，[W3C组织](https://en.wikipedia.org/wiki/World_Wide_Web_Consortium)发布；
* HTML 4.0.1：1999年12月24日，[W3C组织](https://en.wikipedia.org/wiki/World_Wide_Web_Consortium)发布；
* XHTML 1.0：2001年1月26日，[W3C组织](https://en.wikipedia.org/wiki/World_Wide_Web_Consortium)发布。

### 1.1.2. HTML 4.0.1和XHTML

**XHTML**：eXtensible Hype Text Markup Language，扩展的超文本标记语言。XHTML 是更严格、更纯净的HTML，兼容HTML 4.0.1 。

### 1.1.3. 文档类型定义（DTD）

**DTD**（Document Type Detinition，文档类型定义），用于定义HTML和XHTML的语法约束。

### 1.1.4. 从XHTML到HTML 5

**HTML 5**：“妥协式”的规范。

## 1.2. HTML 5 的优势

* 解决跨浏览器问题；

|     | Chrome | Firefox | Safari |   IE    | Opera |
| :-: | :----: | :-----: | :----: | :-----: | :---: |
| 内核 | Blink  |  Gecko  | Webkit | Trident | Blink |

* 部分替代了JavaScript，简化了代码；
* 更加明确的语义支持；
* 增强了Web应用程序的功能；

## 1.3. HTML 5 的基本结构和语法变化

HTML 5 遵守的3点规则：
* 兼容性
* 实用性
* 非革命性的发展

### 1.3.1. HTML 5 基本结构

```
<!DOCTYPE html>
```

HTML 5文档基础结构
```
<!DOCTYPE html>
<html>
<head>
    <title>页面标题</title>
    <meta http-equiv="Content-Type" content="text/html;charset=gb2312"/>
</head>
</body>
页面内容
</body>
</html>
```

### 1.3.2. HTML 5 的语法变化

* 标签不再区分大小写；
W3C提供了一个在线验证页面是否符合规范的网站：[在线验证](http://validator.w3.org/)。

* 元素可以省略结束标签
HTML 5 中的省略标签可以分为以下三种：
  * 空元素语法的元素：area、base、br、col、command、embed、hr、img、input、keygen、link、meta、param、source、wbr
   这些空元素不允许将开始标签与结束标签分开定义。例如，<img.../>元素不允许写成以下形式：
     ```
      <img src="./img.png" alt="a"></img>
     ```
    其正确书写格式为：
     ```
      <img src="./img.png" alt="a"/>
      ```
      
  * 可以省略结束标签的元素：colgroup、dt、dd、li、optgroup、option、p、rt、rp、thead、tbody、tfoot、tr、td、th
 
  * 可以省略全部标签的元素：html、head、body、tbody
 
* 允许省略属性值的属性

* 允许省略属性值不使用引号
