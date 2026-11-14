<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a6a9zi5sj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:field-area" /></template>
<style>
.a6a9zi5sj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 2.5H21.5v13.75H7.75Zm-4.25 0v13.75M2.25 3.75L3.5 2.5l1.25 1.25M2.25 15l1.25 1.25L4.75 15m3 5.25H21.5M9 19l-1.25 1.25L9 21.5M20.25 19l1.25 1.25l-1.25 1.25");
}

</style>
