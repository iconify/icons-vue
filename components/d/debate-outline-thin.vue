<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h_h2a_b1l"/><path class="m0fptpbiy"/><path class="i8-98acrg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:debate-outline-thin" /></template>
<style>
.h_h2a_b1l {
  d: path("M6.5 8.83a3.5 3.5 0 1 1 -2.96 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i8-98acrg {
  d: path("m9 5 3 3 -2 2 3 3 -2 2 2.5 2.5");
}

.m0fptpbiy {
  d: path("M20.5 8.83a3.5 3.5 0 1 1 -2.96 0");
}

</style>
