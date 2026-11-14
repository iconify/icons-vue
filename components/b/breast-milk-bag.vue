<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kpup3visc"/><path class="f6bvecbsp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:breast-milk-bag" /></template>
<style>
.f6bvecbsp {
  d: path("M5.5 12.25q3.5-1.5 6.5 0t6.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kpup3visc {
  d: path("M7 2.5h10Q19 12 18.5 18q-.25 3.5-4 3.5h-5q-3.75 0-4-3.5Q5 12 7 2.5M6.25 6h11.5");
}

</style>
