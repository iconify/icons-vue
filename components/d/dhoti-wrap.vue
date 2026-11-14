<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jainvr19n"/><path class="q4aqqezwo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dhoti-wrap" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jainvr19n {
  d: path("M10.25 4.5H6C4.5 10 3.5 15 3 20.5q4.5-1.5 9 0q4.5-1.5 9 0c-.5-5.5-1.5-10.5-3-16h-4.25");
}

.q4aqqezwo {
  d: path("M10.25 4.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M10 8q-1.25 5-1.5 9.75M14 8q1.25 5 1.5 9.75");
}

</style>
