<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="hvkwn2bqr"/><path class="w7btfvbrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:floya" /></template>
<style>
.hvkwn2bqr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.829 24.71v2.949a2.184 2.184 0 0 1-2.184 2.184h0c-.604 0-1.15-.244-1.545-.64");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.w7btfvbrz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.829 21.106v3.604a2.184 2.184 0 0 1-2.184 2.184h0a2.184 2.184 0 0 1-2.185-2.184v-3.604m-9.553-2.949v7.645c0 .603.489 1.092 1.092 1.092h.327M37.5 24.71a2.184 2.184 0 0 1-2.184 2.184h0a2.184 2.184 0 0 1-2.185-2.184v-1.42c0-1.206.978-2.184 2.185-2.184h0c1.206 0 2.184.978 2.184 2.184m0 3.604v-5.788M19.913 23.29a2.184 2.184 0 0 1 4.368 0v1.42a2.184 2.184 0 0 1-4.368 0zm-8.118 3.604v-7.208a1.53 1.53 0 0 1 1.53-1.529h0c.752 0 1.221.223 1.544.64M10.5 21.106h3.058");
}

</style>
