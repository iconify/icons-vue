<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="x2ho6y6-n"/><path class="x8q41j25v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bearing" /></template>
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

.x2ho6y6-n {
  d: path("M7.5 12a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0");
}

.x8q41j25v {
  d: path("M9.5 5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m6.75 4.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m-2.75 8a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m-8 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m-2.75-8a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
