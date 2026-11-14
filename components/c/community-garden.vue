<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8la_n36f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:community-garden" /></template>
<style>
.c8la_n36f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 15h19v6.5h-19Zm0 3.25h19M5.5 15v-5m0 2C4 12 3.25 11 3.25 9.75c1.25 0 2.25.75 2.25 2.25Zm0-1.5C5.5 9 6.25 8 7.75 8c0 1.5-.75 2.5-2.25 2.5ZM12 15V9m0 2c-1.5 0-2.25-1-2.25-2.25C11 8.75 12 9.5 12 11Zm0-1.5C12 8 12.75 7 14.25 7c0 1.5-.75 2.5-2.25 2.5Zm6.5 5.5v-5m0 2c-1.5 0-2.25-1-2.25-2.25c1.25 0 2.25.75 2.25 2.25Zm0-1.5c0-1.5.75-2.5 2.25-2.5c0 1.5-.75 2.5-2.25 2.5Z");
}

</style>
