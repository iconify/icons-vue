<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="rn9jdob9d"/><path class="gk-c06bwt"/><path class="m8c5cec1e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hearing-dog" /></template>
<style>
.gk-c06bwt {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 11h.01M14 11h.01");
}

.m8c5cec1e {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 14.5h2M3.75 9a6 6 0 0 0 0 6m16.5-6a6 6 0 0 1 0 6");
}

.rn9jdob9d {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.68 4.23l1.64 1.79q.68.73 1.68.73h2q1 0 1.68-.73l1.64-1.79q.68-.73.88.25l.6 3.04q.2.98.05 1.97l-.7 4.52q-.15.99-.87 1.68l-3.56 3.37q-.72.69-1.44 0l-3.56-3.37Q7 15 6.85 14.01l-.7-4.52Q6 8.5 6.2 7.52l.6-3.04q.2-.98.88-.25");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
