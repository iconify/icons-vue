<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="em_zdub9q"/><rect class="c2y6i5h_y"/><circle class="nd0-wufcj"/><circle class="fi92xeb8a"/><circle class="ppc8ufbfp"/><circle class="m7ek3bczk"/><circle class="mh1j0ac4n"/><path class="y5c-7gbxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:device-pulse" /></template>
<style>
.c2y6i5h_y {
  width: 23.316px;
  height: 39px;
  x: 12.342px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.793px;
  ry: 2.793px;
}

.em_zdub9q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.342 11.023h23.316M12.342 36.977h23.316");
}

.fi92xeb8a {
  cx: 16.737px;
  cy: 28.968px;
  r: 1.532px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.m7ek3bczk {
  cx: 26.421px;
  cy: 28.065px;
  r: 1.532px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mh1j0ac4n {
  cx: 31.263px;
  cy: 19.032px;
  r: 1.532px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.nd0-wufcj {
  cx: 24px;
  cy: 40.254px;
  r: 0.75px;
  fill: currentColor;
}

.ppc8ufbfp {
  cx: 21.579px;
  cy: 21.742px;
  r: 1.532px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.y5c-7gbxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.601 27.704l3.178-4.658m1.84-.182l2.837 4.015m1.679-.168l3.383-6.343");
}

</style>
