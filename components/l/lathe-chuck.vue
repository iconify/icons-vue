<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="cg_luebsi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lathe-chuck" /></template>
<style>
.cg_luebsi {
  d: path("M10 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0m2-8za1.25 1.25 0 0 1 1.25 1.25v2A1.25 1.25 0 0 1 12 8.5a1.25 1.25 0 0 1-1.25-1.25v-2A1.25 1.25 0 0 1 12 4m6.928 12za1.25 1.25 0 0 1-1.707.458l-1.732-1a1.25 1.25 0 0 1-.458-1.708a1.25 1.25 0 0 1 1.708-.458l1.732 1A1.25 1.25 0 0 1 18.928 16M5.072 16za1.25 1.25 0 0 1 .457-1.708l1.732-1a1.25 1.25 0 0 1 1.708.458a1.25 1.25 0 0 1-.458 1.708l-1.732 1A1.25 1.25 0 0 1 5.072 16");
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
