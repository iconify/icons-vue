<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="nj5qkke2z"/><path class="b6g-vuagr"/><circle class="n5rez8zhl"/><path class="ggre_cc2e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:diplomat" /></template>
<style>
.b6g-vuagr {
  d: path("M2.75 21.25a5.5 6.5 0 0 1 11 0Z");
}

.ggre_cc2e {
  d: path("M13.75 7.5h7.5M17.5 3.75q-1.35 3.75 0 7.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n5rez8zhl {
  cx: 17.5px;
  cy: 7.5px;
  r: 3.75px;
}

.nj5qkke2z {
  cx: 8.25px;
  cy: 8.25px;
  r: 3px;
}

</style>
