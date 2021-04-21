# Reading notes for CSS 

### Using External Css
Here are some important keywords.

```
<link> is an element that tells the browser where the CSS file is. It requires no closing tag. It resides in the <head>.

*href* is used to tell the path to the css file. 

*type* specifiees the document type being linked. 

*rel* tells the connection between the html page and the file linked to it. When linking a CSS the value should be stylesheet. ```

### Internal CSS

You can directly targer or select elements to change the style of in the style.css file. There are a lot of selectors to targer specific areas. And if you want to target everything you simply use * {}. 

Declarations are made of two parts the properties and the values. 

You can but usually don't have css in the actual index.html file. Usually you just use the Style.css

### Color
You can have colors designated in three ways. 

* RGB values (rnum,bnum,gnum)
* Hex Codes ex. (\#ee3e90).
* Color names (yellow).

```background-color``` sets the box or container to a specific color. 

Choosing the correct color contrast is important. For titles and big things High contrast is best. For long paragraphs use medium contrast.

CSS3 allows you to set the opacity of the color in a RGBA format.

CSS3 also allows you to set the Hue Saturation and Lightnes.