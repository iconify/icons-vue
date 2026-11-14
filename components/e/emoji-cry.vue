<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x6mcg9bap"/><path class="rqds-0b_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:emoji-cry" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rqds-0b_w {
  d: path("M15.5 12.25s1.25 1.5 1.25 2.5a1.25 1.25 0 0 1-2.5 0c0-1 1.25-2.5 1.25-2.5m-7.5 5q1.125-1.5 3-1.5");
}

.x6mcg9bap {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0m6-2.5h.01m6.99 0h.01");
}

</style>
