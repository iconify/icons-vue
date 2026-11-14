<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r7qkslw-m"/><path class="ysj8j5brz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:friend-online" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r7qkslw-m {
  d: path("M6.5 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0m-3 14c0-4.5 3.25-7 7-7c1.25 0 2.25.2 3 .5");
}

.ysj8j5brz {
  fill: currentColor;
  d: path("M15.5 18.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
