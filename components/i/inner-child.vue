<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m7dp62nbu"/><path class="azucj0-jx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:inner-child" /></template>
<style>
.azucj0-jx {
  d: path("M8.25 7a2 2 0 1 1 2-2.5m5.5 2.5a2 2 0 1 0-2-2.5m-3.75 7C5.5 13 5.5 21 9 21h6c3.5 0 3.5-8-1-9.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m7dp62nbu {
  d: path("M8 8a4 4 0 1 0 8 0a4 4 0 1 0-8 0");
}

</style>
