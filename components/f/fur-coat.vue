<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a5p4sdb3z"/><path class="bvvycmfzs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fur-coat" /></template>
<style>
.a5p4sdb3z {
  d: path("m9 3.5l-4.5 2L3 15q.75 1.5 1.75 0q1 1.5 1.75 0L7 9v12.5h10V9l.5 6q.75 1.5 1.75 0q1 1.5 1.75 0l-1.5-9.5l-4.5-2");
}

.bvvycmfzs {
  d: path("M9 3.5L6.5 4.75Q6 7 8 7.5q-.25 2.25 2 2.25q.5 1.75 2 1.75t2-1.75q2.25 0 2-2.25q2-.5 1.5-2.75L15 3.5q-3 2.5-6 0m3 8v10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
