<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c_mjwpm2r"/><path class="qzgpl4b6a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dim-sum-house" /></template>
<style>
.c_mjwpm2r {
  d: path("M2.5 9.5q9.5-5.5 19 0Zm1.5 0v9A1.5 1.5 0 0 0 5.5 20h13a1.5 1.5 0 0 0 1.5-1.5v-9M4 13h16M4 16.5h16");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qzgpl4b6a {
  d: path("M10.25 6.75a1.75 1.75 0 0 1 3.5 0");
}

</style>
