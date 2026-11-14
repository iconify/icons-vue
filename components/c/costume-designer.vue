<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejent2b-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:costume-designer" /></template>
<style>
.ejent2b-r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 4.5A1.75 1.75 0 1 1 12 6.25v.25L4 10h16l-8-3.5M9.5 10l1 3.5L6 21h12l-4.5-7.5l1-3.5");
}

</style>
