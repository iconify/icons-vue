<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="ft37a3bfg"/><path class="x0vfd1bov"/><path class="h-_mr525x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:elephant" /></template>
<style>
.ft37a3bfg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 6h5c3.6 0 6.5 2.9 6.5 6.5v7.75a1 1 0 0 1-1 1h-1.5a1 1 0 0 1-1-1V17.5h-5v2.75a1 1 0 0 1-1 1h-1.5a1 1 0 0 1-1-1V15.5c-2.85-.4-4.5-2.1-4.5-4.5c0-2.75 2.25-5 5-5");
}

.h-_mr525x {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.75 9.75h.01");
}

.x0vfd1bov {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 13.5v4.75a1.25 1.25 0 0 1-2.5 0m7.25-9c3-1 6.25.25 6.25 3.25c0 2.25-1.75 3.5-3.75 3.5c-1.25 0-2.25-.6-2.25-1.5s.6-1.4.6-2.65c0-1-.35-1.85-.85-2.6");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
