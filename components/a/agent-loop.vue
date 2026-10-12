<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="z4cz_y0ft"/><rect class="m9186ibpp"/><path class="np225_bxb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:agent-loop" /></template>
<style>
.m9186ibpp {
  width: 7.5px;
  height: 6px;
  x: 8.25px;
  y: 9px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

.np225_bxb {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.5 12h.01m2.99 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z4cz_y0ft {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M20.5 12a8.5 8.5 0 0 1-14.51 6.01M3.5 12a8.5 8.5 0 0 1 14.51-6.01M18 2.75V6h-3.25M6 21.25V18h3.25");
}

</style>
