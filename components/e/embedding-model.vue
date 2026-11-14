<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e7-92-b-m"/><path class="zh8stpdcj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:embedding-model" /></template>
<style>
.e7-92-b-m {
  d: path("m7.235 7.914l2.5 1.406a1.5 1.5 0 0 1 .765 1.307v2.746a1.5 1.5 0 0 1-.765 1.307l-2.5 1.406a1.5 1.5 0 0 1-1.47 0l-2.5-1.406a1.5 1.5 0 0 1-.765-1.307v-2.746a1.5 1.5 0 0 1 .765-1.307l2.5-1.406a1.5 1.5 0 0 1 1.47 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zh8stpdcj {
  d: path("m2.5 9.75l4 2.25l4-2.25M6.5 12v4.5m6.75-4.5H17m-2-2l2 2l-2 2m5-7h.01M20 12h.01M20 17h.01");
}

</style>
