<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eb8o6ccsq"/><path class="kig4s-blh"/><path class="k_9t8jd5i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:childrens-ward" /></template>
<style>
.eb8o6ccsq {
  d: path("M3 4v16.5m0-6h18v6M3 18h18M11.5 8a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k_9t8jd5i {
  d: path("M11 12.25a2.5 1.75 0 1 0 5 0a2.5 1.75 0 1 0-5 0");
}

.kig4s-blh {
  fill: currentColor;
  d: path("M11 6.25a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0m3.5 0a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0");
}

</style>
