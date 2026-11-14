<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="otxjj3p-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:drawworks" /></template>
<style>
.otxjj3p-t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 13.5a1.75 6.5 0 1 0 3.5 0a1.75 6.5 0 1 0-3.5 0Zm11 0a1.75 6.5 0 1 0 3.5 0a1.75 6.5 0 1 0-3.5 0ZM6.5 10h8m-8 7h8m-4-14.5V10m7.25 3.5h2.75v4");
}

</style>
