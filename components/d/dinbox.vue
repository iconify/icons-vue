<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xlx7m6bzd"/><circle class="sobqxac9r"/><path class="iy4y24b0x"/><circle class="q-ttrglwb"/><path class="bnr2_2bjf"/><circle class="ches4mbwm"/><path class="h84ey5bjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dinbox" /></template>
<style>
.bnr2_2bjf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.5 30.6h10.2m3.8 3.8l-3.8-3.8");
}

.ches4mbwm {
  cx: 29.7px;
  cy: 26.7px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.h84ey5bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.4 26.7h21.7");
}

.iy4y24b0x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.5 22.6h10.2m3.8-3.8l-3.8 3.8");
}

.q-ttrglwb {
  cx: 18px;
  cy: 36.4px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.sobqxac9r {
  cx: 24px;
  cy: 16.7px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xlx7m6bzd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.5 11.6v29.9c0 1.1-.9 2-2 2h-27c-1.1 0-2-.9-2-2V11.6L24 4.5z");
}

</style>
