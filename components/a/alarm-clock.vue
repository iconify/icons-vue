<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect transform="rotate(-44.72 9.028 9.839)" class="v9ptlgrut"/><rect transform="rotate(-45.28 38.976 9.838)" class="yiyziekrt"/><circle class="r4y01nbqt"/><path class="g3o9-tbfc"/><circle class="vutsr8b5o"/><path class="ctbp7-byb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:alarm-clock" /></template>
<style>
.ctbp7-byb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.1 12.28v10.93m1.64 1.63h7.84");
}

.g3o9-tbfc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.88 37.76l-1.18 4.92m23.62-4.92l1.18 4.92");
}

.r4y01nbqt {
  cx: 24.1px;
  cy: 24.84px;
  r: 17.11px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.v9ptlgrut {
  width: 9.25px;
  height: 4.62px;
  x: 4.41px;
  y: 7.52px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.92px;
}

.vutsr8b5o {
  cx: 24.1px;
  cy: 24.84px;
  r: 1.63px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yiyziekrt {
  width: 4.62px;
  height: 9.25px;
  x: 36.66px;
  y: 5.21px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.92px;
}

</style>
