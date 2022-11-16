<template>
  <div class="home">
    <img is="artportfolio-logo" alt="Vue logo" src="../assets/Zoe's art portfolio.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import Main from '@/components/Main.vue'

export default {
  name: 'Home',
  components: {
    Main
  }
}
</script>
<styles>
#artportfolio-logo{
  
}
</styles>
