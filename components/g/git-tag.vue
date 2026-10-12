<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="lejn8kbnn"/><circle class="esuf5po8m"/><path class="le63thb5s"/><path class="by03byron"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:git-tag" /></template>
<style>
.by03byron {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.25 12h.01");
}

.esuf5po8m {
  cx: 5.75px;
  cy: 12px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.le63thb5s {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.5 8.25h5q1.25 0 2.1.91l1.8 1.93q.85.91 0 1.82l-1.8 1.93q-.85.91-2.1.91h-5q-1.25 0-1.25-1.25v-5q0-1.25 1.25-1.25");
}

.lejn8kbnn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 2.75v7m0 4.5v7");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
