<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zrzo0pbze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:jhalmuri" /></template>
<style>
.zrzo0pbze {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m19 8.5l-7 10l-7-10c0-3 2.5-4 4-3c1-3 5-3 6 0c1.5-1 4 0 4 3Zm-14 0h14M10.5 21l1.5-2.5l1.5 2.5Z");
}

</style>
