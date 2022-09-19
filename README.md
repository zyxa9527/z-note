# z-note

這是一個類似CodePen,CodeSandBox環境的code編輯器,並且還可以使用markdown語法撰寫註記

- 點選Code按鈕撰寫code,Text按鈕撰寫markdown
- 任何撰寫的code或markdown可以被保存在檔案裡,並且被引用
- 增加 ![#f03c15](https://via.placeholder.com/15/f03c15/f03c15.png) `show` 方法,可在在環境內立即執行 e.g: string,number,React component
- 刪除或排序任何cell
- 在cell中可自由在中間新增cell

任何編輯都會儲存在檔案中 
執行 ![#f03c15](https://via.placeholder.com/15/f03c15/f03c15.png) `npx zbook serve test.js`
所有編輯即會在  ![#f03c15](https://via.placeholder.com/15/f03c15/f03c15.png) `test.js` 檔案中



![未命名](https://user-images.githubusercontent.com/60773919/190969487-06ab0e8d-1b64-4480-a186-d587708ba89a.png)


## Technology
- Build project with Redux and Typescript
- Immer library
- Lerna CLI automate deployment 
- Build in-browser transpiler + bundler
- Use Redux middlewares 
- Use Web Assembly to increase the performance


## Installation
```
npx z-note
```

### Project setup
```
npx z-note serve
```
 
![aaa](https://user-images.githubusercontent.com/60773919/190973049-27668fea-2284-4f1e-b668-1e578efd5162.png)
