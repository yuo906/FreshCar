<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <div class = "container">
    <button type="button" class="btn btn-primary">Primary</button>
    <img class = "img-fluid" alt = "Vue logo" src = "./assets/logo.png" />
    <h1 class = "display-1 text-bold"> My App </h1>
    <h1 class = "text-gray-soft text-regular"> Greetings to you all. </h1>
    <HelloWorld msg = "Welcome to Your Vue.js App" />
  </div>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
