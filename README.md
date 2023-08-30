## Chapter 14: Flexbox
It is my coding practice with the TUTORIAL of Dave Gray. 

## Source
### Dave Gray 的 CSS 資源
https://github.com/gitdagray/css_course

### Dave Gray 的 CSS 課程
https://youtube.com/playlist?list=PL0Zuz27SZ-6Mx9fd9elt80G1bPcySmWit

### Dave Gray 的 YouTube 頻道
https://www.youtube.com/@DaveGrayTeachesCode

## Quick Concept outline
###  1. Intro
        教學影片固定的開頭

###  2. Welcome
        歡迎觀眾，說明工具與資料位置

###  3. Setup & Starter Code Review
        初始設定說明

###  4. display: flex
        設定顯示方式為 flex

###  5. justify-content
        (1)設定 justify-content 為 flex-start
        (2)更改 justify-content 為 flex-end
        (3)更改 justify-content 為 center
        (4)新增 div 的 gap間隔為 1rem
        (5)更改 justify-content 為 space-around
        (6)移除 gap間隔觀察是否有差異
        (7)更改 justify-content 為 space-between

###  6. align-items
        修改 .box 屬性的 minheight 為 height
        (1)設定 align-items 為 flex-start
        (2)更改 align-items 為 flex-end
        (3)更改 align-items 為 center

###  7. flex-direction changes everything
        (1)設定 flex-direction 為 column (數字順序由上往下)
        (2)修改 align-items 為 flex-start
        (3)修改 align-items 為 flex-end
        (4)修改 align-items 為 center
        (5)修改 justify-content 為 flex-start
        (6)修改 justify-content 為 flex-end
        (7)修改 justify-content 為 center
        (8)設定 flex-direction 為 row (數字順序由左往右)
        (9)恢復 div 的 gap間隔為 1rem

###  8. Reversing the rows and columns
        (1)設定 flex-direction 為 row-reverse (數字順序由右往左)
        (2)設定 flex-direction 為 column-reverse (數字順序由下往上)

###  9. flex-wrap
        縮小視窗發現 div 會超出視窗的範圍。
        (1)設定 flex-wrap 為 wrap
        (2)設定 flex-direction 為 row，修改數字的順序
        
### 10. flex-flow shorthand
        使用縮寫 flex-flow 取代 flex-direction 和 flex-wrap

### 11. align-content
        (1)設定 align-content 為 flex-start
        (2)設定 align-content 為 flex-end
        (3)設定 align-content 為 center
        (4)設定 align-content 為 space-between
        (5)設定 align-content 為 space-around
        (6)設定 align-content 為 space-evenly

### 12. Flex items can also be flex containers
        設定 display 為 flex，justify-content 為 center，align-items 為 center

### 13. flex-basis
        使用 flex-basis 取代 min-width 的設定

### 14. flex-grow
        (1)設定 .box 屬性的 flex-grow 為 1;
        (2)設定 .box 屬性第二個元素的 flex-grow 為 2;

### 15. flex-shrink
        修改 flex-grow 為 flex-shrink，flex-flow 改為 row nowrap，flex-basis 改為 250px，並縮小視窗

### 16. flex shorthand
        (1)在.box 屬性使用縮寫 flex 設定 flex-grow 為 1，flex-shrink 為 1，flex-basis 為 250px
        (2)在.box 屬性使用縮寫 flex 設定 flex-grow 為 1，flex-shrink 為 1，flex-basis 為 250px；並設定 .box 屬性第二個元素的 flex 為 2 2 250px

### 17. order property
        (1)設定 .box 屬性第二個元素的 order 為 4，移動到最後
        (2)設定 .box 屬性第二個元素的 order 為 0，移動到原本的位置
        (3)設定 .box 屬性第二個元素的 order 為 -1，移動到最前面
        (4)flex-flow 改為 row-reverse wrap
        (5)設定 .box 屬性第二個元素的 order 為 0
        (6)設定 .box 屬性第二個元素的 order 為 1
        (7)flex-flow 改為 row wrap

### 18. Practice with Flexbox Froggy
        Flexbox Froggy - A game for learning CSS flexbox https://flexboxfroggy.com/
