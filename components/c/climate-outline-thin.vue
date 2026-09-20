<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wiyigspfz"/><path class="abchdfb3i"/><path class="ss47z8bxu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:climate-outline-thin" /></template>
<style>
.abchdfb3i {
  d: path("M4 17a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ss47z8bxu {
  d: path("M20 8c0 6 -3 9 -8 9 0 -6 3 -9 8 -9");
}

.wiyigspfz {
  d: path("M7 4v10");
}

</style>
