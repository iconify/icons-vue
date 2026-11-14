<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hnghs_bdn"/><path class="bo_yiprbh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crankbait" /></template>
<style>
.bo_yiprbh {
  d: path("m6.616 12.384l-2.732 2.732A1.084 1.084 0 0 0 4 16.75a1.44 1.44 0 0 0 1.884-.134l2.732-2.732A1.084 1.084 0 0 0 8.5 12.25a1.44 1.44 0 0 0-1.884.134M11.5 10h.01");
}

.hnghs_bdn {
  d: path("M7 10.5c2-4 10-3.5 13.5 0C17 14 9 14.5 7 10.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
