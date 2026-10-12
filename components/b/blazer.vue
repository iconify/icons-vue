<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="z9kda4s-r"/><path class="rcxt2vbbq"/><path class="qs-y-_biw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:blazer" /></template>
<style>
.qs-y-_biw {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 16.5h.01");
}

.rcxt2vbbq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 3.5L8 7.25l1.5.5L12 13.5l2.5-5.75l1.5-.5l-.75-3.75m-.5 12.75h2.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z9kda4s-r {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 3.25h4.5q1.25 0 2.35.58l2.05 1.09q1.1.58 1.23 1.82l1.24 12.02q.13 1.24-1.09 1.5l-1.06.23q-1.22.26-2.47.26h-9q-1.25 0-2.47-.26l-1.06-.23q-1.22-.26-1.09-1.5L4.12 6.74q.13-1.24 1.23-1.82L7.4 3.83q1.1-.58 2.35-.58");
}

</style>
