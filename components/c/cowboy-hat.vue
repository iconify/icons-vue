<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qlt6ubbvb"/><path class="zm5lsg6db"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cowboy-hat" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qlt6ubbvb {
  d: path("M7.5 14.5c0-5 .5-8 2-8c1 0 1.5 1 2.5 1s1.5-1 2.5-1c1.5 0 2 3 2 8Z");
}

.zm5lsg6db {
  d: path("M2.5 11.5C3 14.5 6 17 12 17s9-2.5 9.5-5.5c-1 2-3 3-5 3h-9c-2 0-4-1-5-3m5.25.5h8.5");
}

</style>
