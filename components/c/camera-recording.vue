<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lx51vtv2t"/><path class="imdn0wbjd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:camera-recording" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.imdn0wbjd {
  d: path("m16.244 10.066l3-1.75A1.5 1.5 0 0 1 21.5 9.612v4.776a1.5 1.5 0 0 1-2.256 1.296l-3-1.75a1.5 1.5 0 0 1-.744-1.296v-1.276a1.5 1.5 0 0 1 .744-1.296M5.5 10.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

.lx51vtv2t {
  d: path("M6.875 6h4.25a4.375 4.375 0 0 1 4.375 4.375v3.25A4.375 4.375 0 0 1 11.125 18h-4.25A4.375 4.375 0 0 1 2.5 13.625v-3.25A4.375 4.375 0 0 1 6.875 6");
}

</style>
