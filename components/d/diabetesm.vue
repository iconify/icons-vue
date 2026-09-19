<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xx-s0fbkr"/><circle class="pfczepbyg"/><circle class="vidwp0b1i"/><circle class="d8-3e-hjh"/><circle class="jfllh0r8a"/><path class="g3jd21vmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:diabetesm" /></template>
<style>
.d8-3e-hjh {
  cx: 27.697px;
  cy: 20.248px;
  r: 1.955px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.g3jd21vmn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.16 31.27l2.655-3.387m2.499-.033l2.134 2.608m2.25-.084l4.173-8.346m1.533.175l2.386 9.35m2.218.992l2.154-1.665");
}

.jfllh0r8a {
  cx: 31.2px;
  cy: 33.53px;
  r: 1.955px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pfczepbyg {
  cx: 16.927px;
  cy: 26.332px;
  r: 1.955px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.vidwp0b1i {
  cx: 21.592px;
  cy: 31.979px;
  r: 1.955px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xx-s0fbkr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.997 4.5S10.27 22.19 10.27 29.772a14 14 0 0 0 .074 1.419a1.953 1.953 0 1 1 1.365 3.348h-.001a2 2 0 0 1-.626-.109a13.73 13.73 0 0 0 26.449-2.352a1.953 1.953 0 1 1 .053-3.76C36.14 20.149 23.997 4.5 23.997 4.5");
}

</style>
