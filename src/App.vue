<template>
  <div id="app">
    <h1>黑马头条</h1>
    <div>
      <i class="toutiao iconshipin"></i>
    </div>
    <van-button type="default">默认按钮</van-button>
    <van-button type="primary">主要按钮</van-button>
    <van-button type="info">信息按钮</van-button>
    <van-button type="warning">警告按钮</van-button>
    <van-button type="danger">危险按钮</van-button>
    <!-- <router-view/> 是路由的出口 没了就看不见路由界面了-->
    <router-view/>
  </div>
</template>
<script type="text/javascript">
export default {
  name: 'App'
}
</script>
<style lang="less">
</style>
