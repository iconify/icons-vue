<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pvvd5qbcj"/><path class="k7se-bcon"/><path class="vai2uyy5e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:loan-npa" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k7se-bcon {
  d: path("M13 3.5a8.5 8.5 0 0 1 0 17L11.75 17L14 13.5L11.75 10L14 6.75Z");
}

.pvvd5qbcj {
  d: path("M11 3.5a8.5 8.5 0 0 0 0 17L9.75 17L12 13.5L9.75 10L12 6.75Z");
}

.vai2uyy5e {
  d: path("M14 9.75c-.25-.5-1-1-2-1c-1.25 0-2 .75-2 1.5c0 1.75 4 1 4 3.5c0 .75-1 1.5-2 1.5s-1.75-.5-2-1m2-6.75v1.25m0 6.5v1.25");
}

</style>
