<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="vw5nusbpt"/><path class="wu5-n43oq"/><path class="m5128rjhw"/><path class="u5n0jwmal"/><path class="c76wcqhqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:govmo-alt" /></template>
<style>
.c76wcqhqi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.58 33.355c-3.52-1.71-4.32-6-3.75-10.63c0 0 5.06-1.42 7.56 4.32a14.7 14.7 0 0 1 3.61-9.49a14.7 14.7 0 0 1 3.61 9.46c2.5-5.74 7.56-4.32 7.56-4.32c.57 4.66-.23 8.92-3.75 10.63m-23.81 9.37h32.78m-33.77-4.47h34.76");
}

.m5128rjhw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.61 27.015a53.4 53.4 0 0 0 1.48-10.91c0-5-3.3-10.8-3.3-10.8m-18.18 7.19c3.63.06 11 4.15 12.78 14.55M5.5 15.165c.28 6.31 2.73 14.67 11.08 18.19");
}

.u5n0jwmal {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.39 27.015a53.4 53.4 0 0 1-1.48-10.91c0-5 3.3-10.8 3.3-10.8");
}

.vw5nusbpt {
  cx: 24px;
  cy: 32.385px;
  r: 2.27px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wu5-n43oq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.39 12.495c-3.63.06-11 4.15-12.78 14.55m14.89-11.88c-.28 6.31-2.73 14.67-11.08 18.19");
}

</style>
