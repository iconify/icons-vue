<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="cpr0-1bcb"/><circle class="uj1c13ftj"/><circle class="y6p508btl"/><path class="u-dxj_u3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:enter-the-gungeon" /></template>
<style>
.cpr0-1bcb {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 6px;
  ry: 6px;
}

.u-dxj_u3h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.625 34a3.625 3.625 0 0 1-7.25 0z");
}

.uj1c13ftj {
  cx: 13.125px;
  cy: 34px;
  r: 3.625px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.y6p508btl {
  cx: 34.875px;
  cy: 34px;
  r: 3.625px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
