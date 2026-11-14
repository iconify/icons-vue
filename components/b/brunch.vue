<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="b-9fgdc3k"/><path class="b_i-jbbpm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:brunch" /></template>
<style>
.b_i-jbbpm {
  fill: currentColor;
  d: path("M10.5 11.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.b-9fgdc3k {
  d: path("M7.5 11c0-3.5 3-4.5 5-3.5c2-1.5 5 0 4.5 3c1.5 2-.5 5.5-3 5c-2 2-5.5 1-5.5-1.5c-1.5-.5-1.5-2-1-3");
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
