<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y4k_22w_l"/><path class="v9il_wb-q"/><path class="m-p3hbclp"/><path class="cjsg0ab2y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-pyramid-outline-thin" /></template>
<style>
.cjsg0ab2y {
  d: path("M2 20h20");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m-p3hbclp {
  d: path("M4 15h16");
}

.v9il_wb-q {
  d: path("M6 10h12");
}

.y4k_22w_l {
  d: path("M8 5h8");
}

</style>
