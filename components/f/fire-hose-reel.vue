<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ym7z67-6m"/><path class="sy-njkcul"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fire-hose-reel" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sy-njkcul {
  d: path("M6.5 9.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0m11 0v7m0 0za1.27 1.27 0 0 1 1.253 1.48l-.38 2.28a.885.885 0 0 1-.873.74a.885.885 0 0 1-.873-.74l-.38-2.28A1.27 1.27 0 0 1 17.5 16.5m-7-7h.01");
}

.ym7z67-6m {
  d: path("M3.5 9.5a7 7 0 1 0 14 0a7 7 0 1 0-14 0");
}

</style>
