<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bj420ihpg"/><path class="v07kwxbjs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:art-class" /></template>
<style>
.bj420ihpg {
  d: path("M5.625 2.5h8.25A2.625 2.625 0 0 1 16.5 5.125v4.25A2.625 2.625 0 0 1 13.875 12h-8.25A2.625 2.625 0 0 1 3 9.375v-4.25A2.625 2.625 0 0 1 5.625 2.5M6 12l-2.5 9.5m10-9.5l.551.952M9.75 12v9.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v07kwxbjs {
  d: path("M6.5 7.25Q8.25 5 10 7.25t3.5 0m2.5 8.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-1.75 6c0-1.75 1.75-3 3.75-3s3.75 1.25 3.75 3");
}

</style>
