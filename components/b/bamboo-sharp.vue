<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aggbp6lvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bamboo-sharp" /></template>
<style>
.aggbp6lvb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 2.75H10v18.5H5.75zm7.5 3.5h4.25v15h-4.25zm-7.5 2.5H10m-4.25 6H10m3.25-3.5h4.25m-4.25 5h4.25m0-5.25c.25-2.5 1.75-4 3.75-4.5q-.375 3.375-3.75 4.5Z");
}

</style>
