<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="vzczr5bht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hon" /></template>
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

.vzczr5bht {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.477 21.757v9.249m.051-3.816a2.31 2.31 0 0 1 2.312-2.311h0a2.31 2.31 0 0 1 2.312 2.312v3.815m20.371.041v-3.944a2.39 2.39 0 0 0-2.39-2.39h0a2.39 2.39 0 0 0-2.39 2.39m0 3.944v-6.334m-13.14-2.45a5.345 5.345 0 0 1 10.69 0v3.474a5.345 5.345 0 0 1-10.69 0z");
}

</style>
