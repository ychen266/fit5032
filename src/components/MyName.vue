<!-- src/components/MyName.vue -->
<template>
  <div class="name-card">
    <h2>{{ name }}</h2>
  </div>
</template>

<script setup>
import { ref } from 'vue';


const name = ref('Yiyang Chen');
</script>

<style scoped>
.name-card {
  padding: 1rem;
  text-align: center;
  background-color: #f0f8ff;
  border-radius: 8px;
  margin-top: 1.5rem;
}

h2 {
  color: #2c3e50;
  font-size: 1.8em;
  text-shadow: 1px 1px 2px rgba(0,0,0,0.1);
}
</style>