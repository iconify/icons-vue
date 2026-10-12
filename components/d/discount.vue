<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="by4hqm3_h"/><path class="qjkwypbnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:discount" /></template>
<style>
.by4hqm3_h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.75 3.41l.5.44q.76.66 1.74.47l.65-.13q.99-.2 1.31.75l.21.63q.32.95 1.27 1.27l.63.21q.95.33.75 1.31l-.13.65q-.19.98.47 1.74l.44.5q.66.75 0 1.5l-.44.5q-.66.76-.47 1.74l.13.65q.2.99-.75 1.31l-.63.21q-.95.32-1.27 1.27l-.21.63q-.32.95-1.31.75l-.65-.13q-.98-.19-1.74.47l-.5.44q-.75.66-1.5 0l-.5-.44q-.76-.66-1.74-.47l-.65.13q-.98.2-1.31-.75l-.21-.63q-.32-.95-1.27-1.27l-.63-.21q-.95-.32-.75-1.31l.13-.65q.19-.98-.47-1.74l-.44-.5q-.66-.75 0-1.5l.44-.5q.66-.76.47-1.74l-.13-.65q-.2-.99.75-1.31l.63-.21q.95-.32 1.27-1.27l.21-.63q.32-.95 1.31-.75l.65.13q.98.19 1.74-.47l.5-.44q.75-.66 1.5 0m-3.5 11.34l5.5-5.5");
}

.qjkwypbnm {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 9.5h.01m4.99 5h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
