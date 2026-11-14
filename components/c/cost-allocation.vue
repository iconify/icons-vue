<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="to_k62bjp"/><path class="to3ktcv4h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cost-allocation" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.to_k62bjp {
  d: path("M2.5 12a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

.to3ktcv4h {
  d: path("M6 8.5h1.5a3.5 3.5 0 0 1 0 7H6m6.5-3.5h9M14 12l6-8m-6 8l6 8M17 4h3v3m-.75 2.75L21.5 12l-2.25 2.25M17 20h3v-3");
}

</style>
