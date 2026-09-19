<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="my885ab9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:deku-deals" /></template>
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

.my885ab9y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.5 30.283V17.686h2.834a5.51 5.51 0 0 1 5.512 5.51v1.576a5.51 5.51 0 0 1-5.512 5.511zm10.616.045V17.672h2.847A5.537 5.537 0 0 1 33.5 23.21v1.582a5.537 5.537 0 0 1-5.537 5.537z");
}

</style>
