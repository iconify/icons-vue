<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="us_fj16bl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lifeguard-flag-red" /></template>
<style>
.us_fj16bl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 4h14v9.5H5Zm0-1v18.5M5 8.75h14M8 19.5q1.75-1.5 3.5 0t3.5 0t3.5 0t3 .5");
}

</style>
