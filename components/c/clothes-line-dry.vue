<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgkb-2b9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:clothes-line-dry" /></template>
<style>
.lgkb-2b9s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3v18.5M21 3v18.5M3 5.5h18m-11.5 0L6 8.25l1.5 2.5l1.5-1v8.75h6V9.75l1.5 1l1.5-2.5l-3.5-2.75c-1 1.5-4 1.5-5 0Z");
}

</style>
