<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yrz1xsxfp"/><path class="moyh2rfov"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chess-board" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.moyh2rfov {
  fill: currentColor;
  d: path("M7.75 3.5H12v4.25H7.75Zm8.5 0h4.25v4.25h-4.25ZM3.5 7.75h4.25V12H3.5Zm8.5 0h4.25V12H12ZM7.75 12H12v4.25H7.75Zm8.5 0h4.25v4.25h-4.25ZM3.5 16.25h4.25v4.25H3.5Zm8.5 0h4.25v4.25H12Z");
}

.yrz1xsxfp {
  d: path("M6.125 3.5h11.75A2.625 2.625 0 0 1 20.5 6.125v11.75a2.625 2.625 0 0 1-2.625 2.625H6.125A2.625 2.625 0 0 1 3.5 17.875V6.125A2.625 2.625 0 0 1 6.125 3.5");
}

</style>
