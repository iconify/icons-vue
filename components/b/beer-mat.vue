<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bk9_7iect"/><path class="rznh07bjb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:beer-mat" /></template>
<style>
.bk9_7iect {
  d: path("M9 14.75a9 3.5 0 1 0 6 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rznh07bjb {
  d: path("M9 18v-8l1.5-2.5v-5h3v5L15 10v8Z");
}

</style>
