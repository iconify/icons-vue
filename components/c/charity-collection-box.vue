<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t9061cbsp"/><path class="v0qzlrnlj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:charity-collection-box" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t9061cbsp {
  d: path("M5 6v12.5a7 3 0 0 0 14 0V6");
}

.v0qzlrnlj {
  d: path("M5 6a7 3 0 1 0 14 0A7 3 0 1 0 5 6m5 0h4m-2 11.5l-3-3c-1-1-.75-3 1-3c1 0 1.75.75 2 1.5c.25-.75 1-1.5 2-1.5c1.75 0 2 2 1 3Z");
}

</style>
