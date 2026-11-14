<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s3phe7d5j"/><path class="vrr0vxb2o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:credit-card-tap" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s3phe7d5j {
  d: path("M6.875 4.25h10.25A4.375 4.375 0 0 1 21.5 8.625v6.75a4.375 4.375 0 0 1-4.375 4.375H6.875A4.375 4.375 0 0 1 2.5 15.375v-6.75A4.375 4.375 0 0 1 6.875 4.25M7.5 12h.01");
}

.vrr0vxb2o {
  d: path("M9.99 9.911a3.25 3.25 0 0 1 0 4.178m2.834-5.817a6.5 6.5 0 0 1 0 7.456m3.12-8.603a9.75 9.75 0 0 1 0 9.75");
}

</style>
