<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h01r_5fde"/><path class="upjgw1qam"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:denture-cleaner" /></template>
<style>
.h01r_5fde {
  d: path("m4.5 3l2 18h11l2-18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.upjgw1qam {
  d: path("M8.5 14.5c0 4.5 7 4.5 7 0M8 6.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m4.5 3.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
