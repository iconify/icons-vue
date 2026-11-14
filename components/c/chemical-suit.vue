<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x-l7suibk"/><path class="zsomxbcxw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chemical-suit" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x-l7suibk {
  d: path("M7.5 10V7.5a4.5 4.5 0 0 1 9 0v14H13v-5h-2v5H7.5Zm0 1L4 17m-1.25-.75l2.5 1.5M16.5 11l3.5 6m1.25-.75l-2.5 1.5");
}

.zsomxbcxw {
  d: path("M10 7.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
