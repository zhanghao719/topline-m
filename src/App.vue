<template>
  <div id="app" style="margin: 0 auto;">
    <!-- 根路由出口 -->
    <router-view />
    <van-tabbar v-model="active">
      <van-tabbar-item icon="home-o" dot><a href="/#/">home</a></van-tabbar-item>
      <van-tabbar-item icon="search" info="99"><a href="#">search box</a></van-tabbar-item>
      <van-tabbar-item icon="friends-o" info="99"><a href="#">标签</a></van-tabbar-item>
      <van-tabbar-item icon="setting-o" info="99"><a href="/#/login">login</a></van-tabbar-item>
    </van-tabbar>

  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="less" scoped>
</style>
