<template>
  <div class="hello">

    <mt-header fixed title="投票">
      <router-link to="/" slot="left">
        <mt-button icon="back">返回</mt-button>
       <!-- <mt-button @click="handleClose">关闭</mt-button> -->
      </router-link>
      <mt-button icon="more" slot="right"></mt-button>
    </mt-header>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
