<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wa4wkx2-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:book-swap" /></template>
<style>
.wa4wkx2-a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 2.5h6.5v9H4Zm9.5 0H20v9h-6.5Zm-6.75 0v9m9.5-9v9M4 16.5h16l-2.25-2.25M20 19.5H4l2.25 2.25");
}

</style>
