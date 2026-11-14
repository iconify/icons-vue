<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i34pl-cjo"/><path class="g2_901bzr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:donation-box-books" /></template>
<style>
.g2_901bzr {
  d: path("M6 12V4h4.5v8m3 0l2-7.5l4 1L18 12M6 7h4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i34pl-cjo {
  d: path("m2.5 9l1 3v7.5a2 2 0 0 0 2 2h13a2 2 0 0 0 2-2V12l1-3m-18 3h17");
}

</style>
