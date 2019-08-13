<template>
  <div id="app">
    <template>
      <header>
        <img src="../public/img/header5.png"/>
      </header>
    </template>
    <template>
       <article>
         <div id="update">最近更新</div>
         <el-divider ></el-divider>
        <div id="qiangliqizi">强力棋子</div>
        <el-divider></el-divider>
        <div id="qizichaxun">棋子查询</div>
        <el-divider></el-divider>
        <div id="zhenrogntuijian">阵容推荐</div>
        <el-divider></el-divider>
        <div id="zhuangbeichaxun">装备查询</div>
        <el-divider></el-divider>
        <div id="shuyu">术语</div>
      </article>
    </template>
    <router-view/>
  </div>
</template>

<style lang="scss">
#app {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;  
   background: linear-gradient(90deg, #432C25, #432C25);
}
header img{
  width: 100%;
  height: 100%;
}
article{
  width:70%;
  height: 69%;
  background: white;
  text-align: center;
  align-items: center;
  margin: auto;
  div{
    width: 100%;
    height: 10%;
    text-align: center;
    align-items: center;
    display: flex;
    flex-direction: column;
    justify-content: center;
    font-size: 20px;

  }
}

</style>
