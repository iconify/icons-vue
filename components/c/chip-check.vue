<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hf8qf84mj"/><path class="x9rlzm11s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chip-check" /></template>
<style>
.hf8qf84mj {
  d: path("M10 3.5h4A3.5 3.5 0 0 1 17.5 7v10a3.5 3.5 0 0 1-3.5 3.5h-4A3.5 3.5 0 0 1 6.5 17V7A3.5 3.5 0 0 1 10 3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x9rlzm11s {
  d: path("M14 3.5a2 2 0 0 1-4 0M2.5 8h4m-4 4h4m-4 4h4m11-8h4m-4 4h4m-4 4h4m-12-3.5l1.75 1.75L14.5 11");
}

</style>
