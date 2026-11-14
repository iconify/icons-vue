<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtl_q-2tb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:category-womens-fashion" /></template>
<style>
.gtl_q-2tb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 7c1.5-1 2.75-.5 3.5 1c.75-1.5 2-2 3.5-1c0 2.5-.75 4-1 5.5c2.5 2 5 4.5 5.5 7.5q-8 2.5-16 0c.5-3 3-5.5 5.5-7.5c-.25-1.5-1-3-1-5.5Zm0 0l-1-4.5m8 4.5l1-4.5m-7 10h5");
}

</style>
