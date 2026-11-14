<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j51f-ebgg"/><path class="pntuip2pn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:germ" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j51f-ebgg {
  d: path("M6 12a6 6 0 1 0 12 0a6 6 0 1 0-12 0");
}

.pntuip2pn {
  d: path("M14.5 6L16 5l-1-1.75m3 6.25l1.75.25l.5-1.75M18 14.5l1 1.5l1.75-1m-6.25 3l-.25 1.75l1.75.5M9.5 18L8 19l1 1.75M6 14.5l-1.75-.25l-.5 1.75M6 9.5L5 8L3.25 9M9.5 6l.25-1.75L8 3.75M10 11h.01M14 11h.01");
}

</style>
