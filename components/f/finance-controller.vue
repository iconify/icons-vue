<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3hq11g3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:finance-controller" /></template>
<style>
.r3hq11g3z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 7.25a4 4 0 1 0 8 0a4 4 0 1 0-8 0ZM3.5 21c0-4 3.25-6.5 7.5-6.5c1.084 0 2.037.131 2.954.392M14.75 18l2 2L21 15.75");
}

</style>
