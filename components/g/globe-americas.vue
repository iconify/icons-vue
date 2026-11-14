<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="zr312tbft"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:globe-americas" /></template>
<style>
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

.zr312tbft {
  d: path("M8 7.5c2-1.25 5-1.5 6.5-.5c-.25 1.75-2 2.5-3 3.5c-.25 1.25.5 2 2 2.5c2 .5 2.25 2 1.5 3l-2 2.5c-.75-1.5-1-3-2-4c-1.5-1.25-2.75-2.5-3.25-4c-.25-1-.25-2.5.25-3");
}

</style>
