<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p6ja0gd_l"/><path class="rg79s_ggi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:floor-plane" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p6ja0gd_l {
  d: path("M9.5 12h-3l-4 6h15l4-6h-7");
}

.rg79s_ggi {
  d: path("M11.25 6h1.5a1.75 1.75 0 0 1 1.75 1.75v5.5A1.75 1.75 0 0 1 12.75 15h-1.5a1.75 1.75 0 0 1-1.75-1.75v-5.5A1.75 1.75 0 0 1 11.25 6M9.5 9h5");
}

</style>
