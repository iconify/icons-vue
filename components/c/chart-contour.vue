<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h8aju3zim"/><path class="ovkujtwtb"/><path class="zhzi7rkmu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chart-contour" /></template>
<style>
.h8aju3zim {
  d: path("M10 2.5c4.5-.5 6 2.5 9 3s3 5.5 1.5 8.5c-1.5 3.5-.5 6.5-5.5 7.5c-4.5 1-7.5-2.5-10-3C2 18 2 14 3 11s2-8 7-8.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ovkujtwtb {
  d: path("M11.5 6c2.5-.25 3.5 1.5 5.25 2.25s1.5 3.5.5 5.25c-1 2-1.5 3.75-4.25 4c-2.5.25-4.5-1.5-5.5-3.25S7 10.5 7.75 9C8.5 7.25 9.5 6.25 11.5 6");
}

.zhzi7rkmu {
  d: path("M13 9.5c1.75 0 1.75 1.5 1.5 2.75c-.25 1.5-1 1.75-2.25 1.75c-1.5 0-2-1.25-1.75-2.5s1-2 2.5-2");
}

</style>
