<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ildrluias"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:accountant-access" /></template>
<style>
.ildrluias {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0ZM4 21c0-4 3.5-6.5 8-6.5c1.187 0 2.304.174 3.306.503M13.75 19.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm3.5-1.5L21.5 14m-1.25 1.25l1.5 1.5");
}

</style>
