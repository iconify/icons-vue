<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xlai1z04x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dandruff" /></template>
<style>
.xlai1z04x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 21c0-3.75 3.75-6 8.5-6s8.5 2.25 8.5 6ZM8 8a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm-3 3.75L6.25 13L5 14.25L3.75 13Zm14 0L20.25 13L19 14.25L17.75 13Zm.5-8L20.75 5L19.5 6.25L18.25 5Z");
}

</style>
