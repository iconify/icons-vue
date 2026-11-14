<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pip0k_bkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:category-vegan" /></template>
<style>
.pip0k_bkd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 7.25c1.5-1.5 2.75-.75 5 1c2 1.75 3 3 1.5 4.5l-11.25 7Zm3.815-.044l1.36-4.733m-.211 5.697l3.214-3.83m-2.065 4.794l4.425-2.162");
}

</style>
