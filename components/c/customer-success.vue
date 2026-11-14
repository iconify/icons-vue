<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n7tzrwbuy"/><path class="ky8jxk3sx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:customer-success" /></template>
<style>
.ky8jxk3sx {
  d: path("M7 5H5.5a2 2 0 0 0 0 4h1.75M17 5h1.5a2 2 0 0 1 0 4h-1.75M12 13v3.8m1.8 4.2H7.5v-3.5h3.8m3.45.5l2 2L21 15.75");
}

.n7tzrwbuy {
  d: path("M7 3h10v5A5 5 0 0 1 7 8Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
