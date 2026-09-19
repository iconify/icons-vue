<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><circle class="yxjaadcms"/><path class="v0o8kfb1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:guitar" /></template>
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

.v0o8kfb1a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.15 5.5v13.871m15.7-5.011c2.8 2.28 4.58 5.75 4.58 9.64c0 6.87-5.56 12.43-12.43 12.43S11.57 30.87 11.57 24c0-3.89 1.78-7.36 4.58-9.64m15.7-8.86v13.871M20.518 5.5v37m2.321-37v37m2.322-37v37m2.321-37v37m2.321 0v-37m-11.606 0v37");
}

.yxjaadcms {
  cx: 24px;
  cy: 24px;
  r: 9.085px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
