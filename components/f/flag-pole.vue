<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wwf2dnm-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flag-pole" /></template>
<style>
.wwf2dnm-y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 4.5c3-1.5 5 1.5 8 0c2-1 4-.75 6 .25v7.5c-2-1-4-1.25-6-.25c-3 1.5-5-1.5-8 0Zm0 0V21m-3 0h6");
}

</style>
