<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gbrqekd5k"/><path class="fhkckrbqq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:category-cleaning" /></template>
<style>
.fhkckrbqq {
  d: path("M15 4.5h4.5m-5 3l3.5 4m-9.5-4V10c-3 .5-4.5 2.5-4.5 5v4.5a2 2 0 0 0 2 2h6.5a2 2 0 0 0 2-2V15c0-2.5-1.5-4.5-3-5V7.5");
}

.gbrqekd5k {
  fill: currentColor;
  d: path("M5 2.5h10v5H5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
