<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="i-f81ybtw"/><circle class="jdisfxbxd"/><circle class="g-3eqm_jx"/><circle class="pjj8kpb-k"/><circle class="lrwzc48rr"/><circle class="uwxsgc_re"/><circle class="zmidfz-_n"/><circle class="l8-q_7b6x"/><circle class="khi_gcckh"/><circle class="qy4c8s9bn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:brussels-airlines" /></template>
<style>
.g-3eqm_jx {
  cx: 35px;
  cy: 24px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.i-f81ybtw {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  rx: 4px;
  ry: 4px;
}

.jdisfxbxd {
  cx: 24px;
  cy: 24px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.khi_gcckh {
  cx: 12.5px;
  cy: 35.675px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.l8-q_7b6x {
  cx: 12.5px;
  cy: 12.5px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.lrwzc48rr {
  cx: 13px;
  cy: 24px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pjj8kpb-k {
  cx: 24px;
  cy: 35px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qy4c8s9bn {
  cx: 35.5px;
  cy: 35.5px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.uwxsgc_re {
  cx: 35px;
  cy: 13px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zmidfz-_n {
  cx: 24px;
  cy: 13px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
