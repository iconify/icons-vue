<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s3-lbmb7s"/><path class="zdxha3ibi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dip-pen" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s3-lbmb7s {
  d: path("m7.72 18.906l-3.867-6.329a1.5 1.5 0 0 1-.154-1.223l1.475-4.795A1.5 1.5 0 0 1 6.608 5.5h4.784a1.5 1.5 0 0 1 1.434 1.059l1.475 4.795a1.5 1.5 0 0 1-.154 1.223l-3.867 6.329a1.5 1.5 0 0 1-2.56 0");
}

.zdxha3ibi {
  d: path("M5.5 5.5v-3h7v3m5.25 6s2.5 3.25 2.5 6a2.5 2.5 0 0 1-5 0c0-2.75 2.5-6 2.5-6M9 21v-7.75m-1.5-1.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
