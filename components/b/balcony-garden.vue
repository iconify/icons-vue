<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1blxfb2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:balcony-garden" /></template>
<style>
.g1blxfb2p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14h19m-19 7.5h19M6 14v7.5m6-7.5v7.5m6-7.5v7.5M4 9.5h6L9 14H5Zm3 0V4m0 2.5Q4.5 6.5 4.5 4M7 6.5q2.5 0 2.5-2.5M14 9.5h6L19 14h-4Zm3 0V3m0 3.5q2.5 0 2.5-3");
}

</style>
