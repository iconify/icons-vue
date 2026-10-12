<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="iy_bqcb-v"/><path class="g0yoftb5h"/><path class="ew7v1pbwm"/><path class="htn678bme"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:audio-guide" /></template>
<style>
.ew7v1pbwm {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 16.5h.01");
}

.g0yoftb5h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 6.75h3m-3 3h3");
}

.htn678bme {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15 9.5a3.5 3.5 0 0 1 0 5M18 7a7 7 0 0 1 0 10");
}

.iy_bqcb-v {
  width: 8.5px;
  height: 18.5px;
  x: 3.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
