<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w4ai66b7u"/><path class="wn8ppvbqo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chart-axis-dual" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w4ai66b7u {
  d: path("M3.5 3v17.5h17V3m-17 4h2m-2 4.5h2m-2 4.5h2m15-9h-2m2 4.5h-2m2 4.5h-2");
}

.wn8ppvbqo {
  d: path("m8.5 16l2.5-5.5l2.5 2.5l2.25-5");
}

</style>
