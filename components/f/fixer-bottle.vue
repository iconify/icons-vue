<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_oleufuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fixer-bottle" /></template>
<style>
.r_oleufuv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 7h12v14.5H5Zm2.5-4h7v4h-7ZM17 9.5h1.5a2 2 0 0 1 2 2V14a2 2 0 0 1-2 2H17m-9.25-2.5h6.5");
}

</style>
