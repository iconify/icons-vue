<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ica7y0b5y"/><path class="bgn-7yc5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bike-helmet" /></template>
<style>
.bgn-7yc5l {
  d: path("M2.5 13h19v3h-19Zm4 3c1 5 10 5 11 0");
}

.ica7y0b5y {
  d: path("M3.5 13.5a8.5 8.5 0 0 1 17 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
