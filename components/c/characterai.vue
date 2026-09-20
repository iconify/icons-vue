<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="lv_5qlb1d"/><circle class="htlz04zhy"/><path class="stuxe1bfd"/><circle class="oa0hynmsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:characterai" /></template>
<style>
.htlz04zhy {
  cx: 33.518px;
  cy: 16.853px;
  r: 0.75px;
  fill: currentColor;
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

.lv_5qlb1d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.282 25.898c-.45.9-1.5 1.5-2.55 1.5a3.01 3.01 0 0 1-3-3v-1.95a3.01 3.01 0 0 1 3-3c1.05 0 2.1.6 2.55 1.5");
}

.oa0hynmsr {
  cx: 21.879px;
  cy: 27.148px;
  r: 0.75px;
  fill: currentColor;
}

.stuxe1bfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.518 19.297v8.101m-3.558 0v-8.101m0 5.101a3.01 3.01 0 0 1-3 3a3.01 3.01 0 0 1-3-3v-1.95a3.01 3.01 0 0 1 3-3a3.01 3.01 0 0 1 3 3");
}

</style>
