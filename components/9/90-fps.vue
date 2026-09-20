<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="e6356rbye"/><path class="lxpukwbgw"/><rect class="b4sibgbcr"/><path class="zbuddlxhd"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:90-fps" /></template>
<style>
.b4sibgbcr {
  width: 7.286px;
  height: 10.997px;
  x: 25.274px;
  y: 12.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.643px;
  ry: 3.643px;
}

.e6356rbye {
  cx: 19.083px;
  cy: 16.143px;
  r: 3.643px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.lxpukwbgw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.762 22.156c.607.795 1.532 1.341 3.065 1.341h.256a3.643 3.643 0 0 0 3.643-3.643v-3.711");
}

.zbuddlxhd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.442 35.5v-8.697h2.847c1.61 0 2.915 1.307 2.915 2.92s-1.305 2.922-2.915 2.922h-2.847m7.855 1.902c.533.694 1.202.953 2.132.953h1.288a2.17 2.17 0 0 0 2.17-2.17v-.01a2.17 2.17 0 0 0-2.17-2.169h-1.42c-1.2 0-2.172-.972-2.172-2.172c0-1.202.974-2.176 2.176-2.176h1.28c.931 0 1.6.258 2.133.953m-19.601 3.395h2.827M14.113 35.5v-8.698h4.349");
}

</style>
