<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yd1jazg9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:baker" /></template>
<style>
.yd1jazg9t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 11V8.5a2.5 2.5 0 0 1 .75-4a2.5 2.5 0 0 1 4.5 0a2.5 2.5 0 0 1 .75 4V11Zm.5 0v1a2.5 2.5 0 0 0 5 0v-1M3 21.5c0-2.5 3-4.25 7.5-4.25q.486 0 .948.027M7.5 8.5h6m1.5 13V18a2 2 0 0 1 1-3.5h4a2 2 0 0 1 1 3.5v3.5Z");
}

</style>
