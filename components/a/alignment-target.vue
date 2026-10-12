<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dh0sdhbvt"/><path class="xsxy7_ibl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:alignment-target" /></template>
<style>
.dh0sdhbvt {
  d: path("M12 5.5a6.5 6.5 0 1 1 0 13a6.5 6.5 0 1 1 0-13m0-2.75V5.5m0 13v2.75M2.75 12H5.5m13 0h2.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xsxy7_ibl {
  d: path("M12 8.5q.42 3.08 3.5 3.5q-3.08.42-3.5 3.5q-.42-3.08-3.5-3.5q3.08-.42 3.5-3.5");
}

</style>
