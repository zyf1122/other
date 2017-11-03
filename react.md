## react 要点

* reactjs 小书
* react jsx 语法(需要补充)
* es6基本语法（let const 箭头函数，扩展运算符， class, import ,export）
* react 组件的封装方法(class创建，直接定义， function都可以)

* react 组件的生命周期(
  mount: componentWillMount, componentDidMount
  props: componentWillReceiveProps,
         shouldComponentUpdate
  update: componentWillUpdate, componentDidUpdate
  unmount: componentWillUnMount
  )

* react 组件中的 state(组件内部的状态,可以修改, 但是this.setState的修改属于异步操作),
 props(父组件向子组件之间相互传递数据), （子组件如何修改父组件的数据？）

 ```
 react　state使用的注意点
 1. 不能直接对state赋值， this.state = xxx 是错误的
 2. this.setState(xxx) 修改时异步的操作，不一定会立刻更新
 3. react会将 多个setState进行合并，分批处理，因此多个setState可能只更新一次
 4. this.setState是浅合并修改，需要注意！！！！

 react-bootstrap(组件)
 antd (阿里巴巴的react组件库，包括移动，pc)

 vue中组件库(饿了么开发的移动端，pc端的组件库)
 ```

* react 组件之间的通信
 (父子组件之间props， 兄弟组件之间(event-proxy库)， 任意组件之间通信(redux状态管理))


* redux(状态管理的库，和框架无关)  react-redux(redux在react中使用的库)

* react 全家桶 (react-router, react-redux)

* redux react-redux
```
state ===> {
  one: one() 方法用于修改one
  two: two() 方法用于修改two
  three: three() 方法用于修改three
}

redux 中 createStore(创建stroe), combineReducers(组合多个reducers)
react-redux  中 connect(将某个组件关联到store中的某个特定的state， 只有该state变化时，该组件才会渲染，否则组件是不会渲染的)
 Provider(将store变为所有的组件都可访问)
```

* react-router (单页面前端路由管理库,主要用于单页面应用)
```
Router 包含路由
Link 相当于链接
Route 点击Link是跳转的位置
```

## react-native(XXX)
