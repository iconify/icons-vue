<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zr64otyni"/><path class="sonx_0hzl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:apple-juice" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sonx_0hzl {
  d: path("M12 11c-1.75-1.25-3.75-.25-3.5 2.5s1.75 4.25 3.5 3.5c1.75.75 3.25-.75 3.5-3.5S13.75 9.75 12 11m0 0l1-3");
}

.zr64otyni {
  d: path("M4.5 3h15L18 21.5H6Z");
}

</style>
