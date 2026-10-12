<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="wgxiw4eza"/><path class="hw3g_zuuw"/><path class="x-1fftdvz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cctv" /></template>
<style>
.hw3g_zuuw {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.75 10.75h.01");
}

.wgxiw4eza {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.11 7.16l11.59-3.1q1.45-.39 1.84 1.06l.91 3.38q.39 1.45-1.06 1.84L5.8 13.44q-1.45.39-1.84-1.06L3.05 9q-.39-1.45 1.06-1.84");
}

.x-1fftdvz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.5 13.25l1 4.25h6.25m0-3.5v7");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
