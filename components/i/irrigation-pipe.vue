<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="lucpkfkop"/><path class="p1s_d00ey"/><path class="iy6c0dbab"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:irrigation-pipe" /></template>
<style>
.iy6c0dbab {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.25 20.5h.01");
}

.lucpkfkop {
  width: 14.5px;
  height: 4.5px;
  x: 2.75px;
  y: 13px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.25px;
}

.p1s_d00ey {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 13v4.5m6-4.5v4.5M10 13V9.5m-2 0h4m5.25 5.75c2.25 0 3.75 1.75 4 4.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
