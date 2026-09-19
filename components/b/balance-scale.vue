<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h4jdi9b1w"/><circle class="c4i87bc-d"/><path class="gvffnc5ky"/><g class="y9tr6bcfx"><circle class="jxhv-kukc"/><circle class="tke6hzbvs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:balance-scale" /></template>
<style>
.c4i87bc-d {
  cx: 9.611px;
  cy: 20.112px;
  r: 2.569px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.gvffnc5ky {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m38.389 17.32l-4.111 12.333H42.5z");
}

.h4jdi9b1w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 8.07v31.86m-6.167 0h12.334M9.611 11.153l28.778 6.166M9.611 11.153L5.5 23.486h8.222z");
}

.jxhv-kukc {
  cx: 36.847px;
  cy: 27.18px;
  r: 1.542px;
}

.tke6hzbvs {
  cx: 39.931px;
  cy: 27.18px;
  r: 1.542px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
