# vue-icon-svg
> 原作者git地址：https://github.com/cenkai88/vue-svg-icon
> 在原来的项目基础上做了一下改进
- 去掉了console.浏览器的输出
- 更改了图标路径 为src/assets/svg



**demo:** https://cenkai88.github.io/vue-svg-icon/demo/  
**features:** 
- **no need to inject SVG in main.js anymore**
- support path, circle, ellipse, rect, line, polyline, polygon tag of SVG
- support grouped tags in SVG
- real-time svg editing in illustrator or sketch
- dynamically set the color of ONE PART of the svg through css 'color' property  
- **an awesome SVG icon site [iconfont](http://www.iconfont.cn)**

## Usage
### 1. install
```
npm install vue-svg-icon --save-dev
```
### 2. put your svg into src/svg/
- **this dir are not supported to be configured now**  
- **src folder should be in the same folder with node_modules**

### 3. import vue-svg-icon in your main.js
```
import Icon from 'vue-svg-icon/Icon.vue';
Vue.component('icon', Icon);  
```
### 4. use the svg icon in your vue!
```
<icon name="chameleon" :scale="20"></icon>
```


