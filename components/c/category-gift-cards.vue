<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v84ne_b1u"/><path class="dhky-mbcw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:category-gift-cards" /></template>
<style>
.dhky-mbcw {
  d: path("M9 12c-1-4-4.25-4.5-4.25-2c0 2 2.25 2.5 4.25 2m0 0c1-4 4.25-4.5 4.25-2c0 2-2.25 2.5-4.25 2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v84ne_b1u {
  d: path("M2.5 7.7V5h19v14h-19v-6.7m5-7.3v.9m0 9.4V19m3-14v.9m0 9.4V19m4.5-3.5h4");
}

</style>
