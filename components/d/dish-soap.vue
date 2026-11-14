<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gt78ibbvo"/><path class="gr7dusbhc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dish-soap" /></template>
<style>
.gr7dusbhc {
  d: path("M9.5 15.25a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

.gt78ibbvo {
  d: path("M6 11a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v8.5a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2Zm3.5-7.5H17v2m-5-2V9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
