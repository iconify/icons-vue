<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="w1vbq6bxq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:biodiversity" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oy9aotbsd {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0");
}

.w1vbq6bxq {
  d: path("M6.5 15.5c-.5-4 1-6.5 4.25-7.25c.5 3.75-1 6.5-4.25 7.25m7-3.5c1.25-2.25 3-2.25 3.75 0l1.5-1.5v3l-1.5-1.5c-.75 2.25-2.5 2.25-3.75 0");
}

</style>
