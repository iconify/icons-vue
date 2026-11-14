<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ybwbp1b2z"/><path class="nwnlv8bvn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cow" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nwnlv8bvn {
  d: path("M8.5 6c-2.5-.5-4-1.75-4-3.5m11 3.5c2.5-.5 4-1.75 4-3.5m-13 5.75C5 7.75 3 8 2.5 9.75c1 1.25 2.75 1.25 4 .75m11-2.25c1.5-.5 3.5-.25 4 1.5c-1 1.25-2.75 1.25-4 .75m-8 0h.01m4.99 0h.01M10 17h.01M14 17h.01");
}

.ybwbp1b2z {
  d: path("M8 6h8a1.5 1.5 0 0 1 1.5 1.5v5c0 1 .5 1.5.5 3.5a4.5 4.5 0 0 1-4.5 4.5h-3A4.5 4.5 0 0 1 6 16c0-2 .5-2.5.5-3.5v-5A1.5 1.5 0 0 1 8 6");
}

</style>
