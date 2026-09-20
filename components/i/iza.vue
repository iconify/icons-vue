<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="lu8xy8nxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:iza" /></template>
<style>
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

.lu8xy8nxf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.68 19.905h6.182l-6.182 8.19h6.182m8.402-3.09a3.09 3.09 0 0 1-6.182 0v-2.01a3.09 3.09 0 0 1 6.182 0m0 5.1v-8.19m-20.528 0h1.348v7.207c0 .543.44.983.983.983h.837");
}

</style>
