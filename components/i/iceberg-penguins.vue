<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vk261ubmw"/><path class="a7a_ombjs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:iceberg-penguins" /></template>
<style>
.a7a_ombjs {
  d: path("M9 10c-.75-2.5-.25-5 1.5-6.5c.75-.75 1.75-.25 2 .5l1.25.75l-1 .5C13.5 7 13.5 8.5 13 10M2.5 19.5q2.25-1.25 4.75 0q2.25 1.25 4.75 0q2.25-1.25 4.75 0q2.25 1.25 4.75 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vk261ubmw {
  d: path("m4.733 13.118l1.818-2.5A1.5 1.5 0 0 1 7.764 10h5.062a1.5 1.5 0 0 1 1.122.503l.769.866a1.396 1.396 0 0 0 1.783.256a1.307 1.307 0 0 1 1.724.306l1.026 1.319a1.394 1.394 0 0 1-1.1 2.25H5.946a1.5 1.5 0 0 1-1.213-2.382");
}

</style>
