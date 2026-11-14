<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0j9l2b8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:disco-ball" /></template>
<style>
.j0j9l2b8j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 13.25a8.25 8.25 0 1 0 16.5 0a8.25 8.25 0 1 0-16.5 0ZM12 2.5V5m-3 .5V21m6-15.5V21M4.25 10.25h15.5m-15.5 6h15.5");
}

</style>
