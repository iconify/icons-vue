<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oar6k8tsc"/><path class="lmea88gly"/><path class="r4ckoabba"/><circle class="w8q8ss4pf"/><circle class="s-t13mbri"/><circle class="edyjoggzv"/><path class="gpht0bbjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:honeygain" /></template>
<style>
.edyjoggzv {
  cx: 34.985px;
  cy: 11.38px;
  r: 2.052px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.gpht0bbjj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.26 18.99c.985-1.223 3.242-3.457 6.112-3.79m-8.795 3.271a8.93 8.93 0 0 1 2.733-5.932");
}

.lmea88gly {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.012 18.455H10.729a6.23 6.23 0 1 0 3.874 11.072l.017.021Z");
}

.oar6k8tsc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.012 18.455a10.108 10.108 0 0 1 0 20.217c-5.388 0-16.96-1.92-20.079-7.759");
}

.r4ckoabba {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.971 34.794l-8.264 2.859l4.226-6.74m13.801-7.873c-1.921 3.472-1.738 11.395 3.997 15.538M17.383 27.557c-.74 1.52.053 6.2 2.313 9.595");
}

.s-t13mbri {
  cx: 41.448px;
  cy: 15.309px;
  r: 2.052px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.w8q8ss4pf {
  cx: 31.962px;
  cy: 25.732px;
  r: 2.79px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
