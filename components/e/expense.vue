<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect transform="rotate(-15.009 24.02 25.245)" class="xv7ijl1wc"/><path class="byijsvbdc"/><rect transform="rotate(-15.009 15.289 25.954)" class="ighfxvt-g"/><path class="mublwvyhv"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:expense" /></template>
<style>
.byijsvbdc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.1 15.2c-.398-1.49.475-3 1.96-3.4l6.57-1.76c1.48-.398 3 .479 3.39 1.97");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ighfxvt-g {
  width: 5.871px;
  height: 4.45px;
  x: 12.354px;
  y: 23.729px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.649px;
  ry: 0.649px;
}

.mublwvyhv {
  fill: none;
  stroke: currentColor;
  stroke-dasharray: 0 0 5 3;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.7 31.4l20-5.37");
}

.xv7ijl1wc {
  width: 30.304px;
  height: 19.602px;
  x: 8.867px;
  y: 15.444px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.91px;
  ry: 2.91px;
}

</style>
