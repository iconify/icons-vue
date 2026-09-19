<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="diz52ulmr"/><circle class="v59-1undn"/><path class="chv-d7boy"/><circle class="s6x31ob9b"/><circle class="e6cmezb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:arplan-3d" /></template>
<style>
.chv-d7boy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 8.733h5.642M5.5 23.746h5.642M5.5 16.24h3.578M5.5 38.759h5.642M5.5 31.253h3.578");
}

.diz52ulmr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.12 27.49v7.24c0 4.29-3.48 7.77-7.78 7.77m7.78-31.57V5.5");
}

.e6cmezb3i {
  cx: 28.157px;
  cy: 19.209px;
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

.s6x31ob9b {
  cx: 28.157px;
  cy: 19.209px;
  r: 7.346px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.v59-1undn {
  cx: 28.157px;
  cy: 19.209px;
  r: 10.253px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
