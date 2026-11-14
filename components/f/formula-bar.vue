<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m90ljyd-i"/><path class="bdlmm7bix"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:formula-bar" /></template>
<style>
.bdlmm7bix {
  d: path("M8.75 9c-.5-.25-1.25-.25-1.5.5l-.5 4.5c-.25 1-.75 1.25-1.5 1m0-4h3m.75.25l2.25 3m0-3l-2.25 3m4.25-6.75v9m2.5-4.5H19");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m90ljyd-i {
  d: path("M5.5 7.5h13A3.5 3.5 0 0 1 22 11v2a3.5 3.5 0 0 1-3.5 3.5h-13A3.5 3.5 0 0 1 2 13v-2a3.5 3.5 0 0 1 3.5-3.5");
}

</style>
