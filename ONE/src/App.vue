<template>
  <div id="app">
    
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import Date from './components/Date.vue';
@Component({
  components:{
    Date
  }
})
export default class App extends Vue {
  
}
</script>
<style lang="stylus">
#app
  position absolute
  top 15vh
  bottom 15vh
  left 20vw
  right 20vw
  background-color #f5f5f5
  box-shadow 15px 5px 10px 5px #666
</style>
