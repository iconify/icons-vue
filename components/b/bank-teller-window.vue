<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z-77h310d"/><path class="aoxgo2bor"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bank-teller-window" /></template>
<style>
.aoxgo2bor {
  d: path("M9.75 7a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m-1.5 8c0-2 1.5-3.5 2.75-3.75M15.75 15c0-2-1.5-3.5-2.75-3.75M10 15a2 2 0 0 1 4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z-77h310d {
  d: path("M6.75 2.5h10.5A1.75 1.75 0 0 1 19 4.25v9A1.75 1.75 0 0 1 17.25 15H6.75A1.75 1.75 0 0 1 5 13.25v-9A1.75 1.75 0 0 1 6.75 2.5M4 17.5h16a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5H4A1.5 1.5 0 0 1 2.5 19A1.5 1.5 0 0 1 4 17.5");
}

</style>
