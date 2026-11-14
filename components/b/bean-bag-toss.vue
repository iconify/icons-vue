<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w649j5kop"/><path class="fg-r90bfe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bean-bag-toss" /></template>
<style>
.fg-r90bfe {
  d: path("M10 16.75a3 1.75 0 1 0 6 0a3 1.75 0 1 0-6 0m6.746-14.165l1.932.518a1.75 1.75 0 0 1 1.237 2.143l-.518 1.932a1.75 1.75 0 0 1-2.143 1.237l-1.932-.518a1.75 1.75 0 0 1-1.237-2.143l.518-1.932a1.75 1.75 0 0 1 2.143-1.237M3 9.5q2.5-5 8-5.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w649j5kop {
  d: path("m3.684 19.001l2.842-6A1.75 1.75 0 0 1 8.107 12h10.628a1.75 1.75 0 0 1 1.581 2.499l-2.842 6a1.75 1.75 0 0 1-1.581 1.001H5.265a1.75 1.75 0 0 1-1.581-2.499");
}

</style>
