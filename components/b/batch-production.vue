<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgkysvpii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:batch-production" /></template>
<style>
.bgkysvpii {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 3h8.5v6.75h-8.5ZM2.5 12.5h8V21h-8Zm11 0h8V21h-8ZM12 3v3m-5.5 6.5v3m11-3v3");
}

</style>
