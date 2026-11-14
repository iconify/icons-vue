<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z9t64tbco"/><path class="v00qn6byd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dependency-locked" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v00qn6byd {
  d: path("m5.25 13.5l2 2l2-2m7.5 4h2.5A1.75 1.75 0 0 1 21 19.25v.5a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 15 19.75v-.5a1.75 1.75 0 0 1 1.75-1.75m-.25 0v-1a1.5 1.5 0 0 1 3 0v1");
}

.z9t64tbco {
  d: path("M5.125 3h4.25A2.625 2.625 0 0 1 12 5.625v.25A2.625 2.625 0 0 1 9.375 8.5h-4.25A2.625 2.625 0 0 1 2.5 5.875v-.25A2.625 2.625 0 0 1 5.125 3m0 12.5h4.25A2.625 2.625 0 0 1 12 18.125v.25A2.625 2.625 0 0 1 9.375 21h-4.25A2.625 2.625 0 0 1 2.5 18.375v-.25A2.625 2.625 0 0 1 5.125 15.5m2.125-7v7");
}

</style>
