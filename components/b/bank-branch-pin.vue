<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e7i1awb-d"/><path class="cevv3ab7j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bank-branch-pin" /></template>
<style>
.cevv3ab7j {
  d: path("m10 7.75l1.012-.886a1.5 1.5 0 0 1 1.976 0L14 7.75a.999.999 0 0 1-.658 1.75h-2.684A.999.999 0 0 1 10 7.75M9.25 9.5v4m2.75-4v4m2.75-4v4M8 13.5h8");
}

.e7i1awb-d {
  d: path("M12 21.5c-4-4-7.5-7.75-7.5-11.75a7.5 7.5 0 0 1 15 0c0 4-3.5 7.75-7.5 11.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
