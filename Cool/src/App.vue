<template>
  <div>
    <my-planet></my-planet>
  </div>
</template>

<script>

import MyPlanet from "./components/planet/planet.vue" 

export default {
  name: 'App',
  components:{
    MyPlanet
  }
}
</script>

<style lang="scss" scoped>
  div{
    color:pink;
    p{
      color:blue
    }
  }
</style> 