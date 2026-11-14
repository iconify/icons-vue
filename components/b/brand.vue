<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="d0rbdmchm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:brand" /></template>
<style>
.d0rbdmchm {
  fill: currentColor;
  d: path("m12.625 8.875l.283.849a1.5 1.5 0 0 0 1.423 1.026h.966A.707.707 0 0 1 15.75 12l-.764.637a1.5 1.5 0 0 0-.489 1.539l.253.949a.713.713 0 0 1-1.095.77l-.801-.554a1.5 1.5 0 0 0-1.708 0l-.801.554a.713.713 0 0 1-1.095-.77l.253-.949a1.5 1.5 0 0 0-.489-1.539L8.25 12a.707.707 0 0 1 .453-1.25h.966a1.5 1.5 0 0 0 1.423-1.026l.283-.849a.659.659 0 0 1 1.25 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oy9aotbsd {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0");
}

</style>
