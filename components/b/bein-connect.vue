<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="empj-2_sn"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bein-connect" /></template>
<style>
.empj-2_sn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.991 19.844a3.616 3.616 0 1 1 .564-1.94h-4.13m-11.925 0a3.617 3.617 0 1 0 7.233 0a3.617 3.617 0 1 0-7.233 0v-6.318m19.437 9.83v-5.148c0-1.725 2.246-2.563 3.328-1.037c1.128 1.59 3.018 5.428 3.018 5.428c.847 1.405 3.217.5 3.217-.992v-5.276m-11.355 0v7.025m1.594 9.527l-9.478 5.472V25.471z");
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

</style>
