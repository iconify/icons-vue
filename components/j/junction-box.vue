<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="a83q7bbzh"/><path class="hjnn2590o"/><path class="kdt-km19y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:junction-box" /></template>
<style>
.a83q7bbzh {
  width: 13.5px;
  height: 13.5px;
  x: 5.25px;
  y: 5.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.75px;
}

.hjnn2590o {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.5 8.5h.01m6.99 7h.01");
}

.kdt-km19y {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 5.25v-2.5m0 16v2.5M5.25 12h-2.5m16 0h2.5M12.9 8.75l-2 3.25h2.25l-2 3.25");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
