<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="tj-5e_utu"/><path class="vf40gxbml"/><path class="k4m13-bnk"/><rect class="re8n8bbea"/><path class="gd5dswbaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:goldenergy" /></template>
<style>
.gd5dswbaq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.442 21.125a2.803 2.803 0 1 1 5.606 0v1.821a2.803 2.803 0 1 1-5.606 0zm8.544-6.521v9.786c0 .772.626 1.398 1.398 1.398h.42m8.018-4.718a2.85 2.85 0 1 0-5.701 0v1.853a2.85 2.85 0 1 0 5.701 0m0 2.85V14.371");
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

.k4m13-bnk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.5 27.839v2.388a1.448 1.448 0 1 1-2.895 0V27.84m-22.893-9.686v7.818a2.606 2.606 0 0 1-2.606 2.606a2.6 2.6 0 0 1-1.843-.763");
}

.re8n8bbea {
  width: 5.212px;
  height: 6.906px;
  x: 8.5px;
  y: 18.154px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.606px;
  ry: 2.606px;
}

.tj-5e_utu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.153 30.967a1.45 1.45 0 0 1-2.71-.718v-.943a1.45 1.45 0 0 1 2.9 0v.471h-2.901M27.805 30.9a1.454 1.454 0 0 1-2.717-.72v-.946a1.454 1.454 0 0 1 2.908 0v.473h-2.909m-1.437 2.022v-2.433a1.475 1.475 0 1 0-2.95 0m.001 2.433v-3.908m8.692 1.429c0-.801.65-1.45 1.451-1.45m-1.451-.001v3.847m5.435-3.87v4.354a1.452 1.452 0 0 1-2.478 1.026");
}

.vf40gxbml {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.376 31.622zc-.801 0-1.451-.65-1.451-1.452v-.943a1.451 1.451 0 0 1 2.903 0v.943c0 .802-.65 1.452-1.452 1.452m6.124-1.395v1.954a1.448 1.448 0 0 1-2.471 1.024");
}

</style>
