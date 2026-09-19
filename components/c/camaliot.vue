<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="qtgsqktdi"/><path class="tob_t-fjk"/><ellipse class="n71rtjbnc"/><path class="ms_m3i7ng"/><circle class="qfjju6baa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:camaliot" /></template>
<style>
.ms_m3i7ng {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.619 11.675a21.495 21.495 0 1 1-5.362-5.341");
}

.n71rtjbnc {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 7.307px;
  ry: 14.5px;
}

.qfjju6baa {
  cx: 39.203px;
  cy: 8.797px;
  r: 3.758px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qtgsqktdi {
  cx: 24px;
  cy: 24px;
  r: 14.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tob_t-fjk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 24h29m-27.023-7.307h25.046M11.478 31.307h25.044M24 38.5v-29");
}

</style>
