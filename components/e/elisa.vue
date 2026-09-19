<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="jc1oydeao"/><rect class="w09ki2bky"/><rect class="y7pu3yb4i"/><circle class="h73had9ed"/><path class="w_vy3abyc"/><circle class="l5pkxji_k"/><path class="yfu3igbyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:elisa" /></template>
<style>
.h73had9ed {
  cx: 15.1px;
  cy: 24px;
  r: 3.409px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jc1oydeao {
  width: 39px;
  height: 31px;
  x: 4.5px;
  y: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.l5pkxji_k {
  cx: 32.9px;
  cy: 24px;
  r: 3.409px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.w_vy3abyc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.212 20.591a5.32 5.32 0 0 1 0 6.819");
}

.w09ki2bky {
  width: 32px;
  height: 19px;
  x: 8px;
  y: 12.245px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
  ry: 1px;
}

.y7pu3yb4i {
  width: 24.617px;
  height: 6.818px;
  x: 11.692px;
  y: 20.591px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.409px;
  ry: 3.409px;
}

.yfu3igbyz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m41.299 39.077l-2.477-5.207H9.178l-2.476 5.207");
}

</style>
