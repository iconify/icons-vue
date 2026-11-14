<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lbdr6bbxb"/><path class="l7jzwo9os"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:category-tv-video" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l7jzwo9os {
  d: path("M9 9.253v2.494a1.75 1.75 0 0 0 2.613 1.522l2.2-1.246a1.75 1.75 0 0 0 0-3.046l-2.2-1.246A1.75 1.75 0 0 0 9 9.253");
}

.lbdr6bbxb {
  d: path("M5.5 3.5h13A3.5 3.5 0 0 1 22 7v7a3.5 3.5 0 0 1-3.5 3.5h-13A3.5 3.5 0 0 1 2 14V7a3.5 3.5 0 0 1 3.5-3.5m1.5 14l-1 3m11-3l1 3");
}

</style>
