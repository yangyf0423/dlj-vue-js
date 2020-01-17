<template>
  <div id="app">
    <div class="title">短链接平台</div>
  </div>
</template>

<script>
export default {
  name: 'app',
  components: {
  }
}
</script>

<style lang="stylus">
*
  padding 0
  margin 0
html,body
  width 100%
  height 100%
#app
  width 100%
  height 100%
  background #fcded4
  .title
    width 100%
    height 80px
    text-align center
    font-size 55px
    position relative
    top 10%
    letter-spacing 5px
    color #fcd8d4
    text-shadow 0 0 0 #b23131, 0 0 3px #b23131, 0 0 6px #b23131, 0 0 9px #b23131, 0 0 12px #b23131
</style>
