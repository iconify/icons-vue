<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="vnvcwwb_m"/><path class="dw79vzb0u"/><path class="ild03l6mn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:donkey" /></template>
<style>
.dw79vzb0u {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.9 15.5c2.75.75 5.45.75 8.2 0");
}

.ild03l6mn {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.25 11h.01m3.49 0h.01m-3.01 7h.01m2.49 0h.01");
}

.vnvcwwb_m {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 9.25c.75-1 2-1.5 3.5-1.5s2.75.5 3.5 1.5c.5 2.25.85 4.5.75 6.5l.5 1.25c.6 1.75-.5 3.5-2.25 3.5h-5c-1.75 0-2.85-1.75-2.25-3.5l.5-1.25c-.1-2 .25-4.25.75-6.5m.75-3.75C8.5 3.75 7 2.75 5.25 2.75c0 1.75 1 3.25 2.75 4Zm5.5 0c.75-1.75 2.25-2.75 4-2.75c0 1.75-1 3.25-2.75 4Z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
