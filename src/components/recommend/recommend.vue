<template>
  <div class="recommend" ref="recommend">
    <scroll ref="scroll" class="recommend-content" :data="discList"></scroll>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  data () {
    return {
      name: 'recommend',
      discList: []
    }
  }
}
</script>

<style lang="stylus" scoped>
</style>
