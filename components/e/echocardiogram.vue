<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zio-17hlh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:echocardiogram" /></template>
<style>
.zio-17hlh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.5 20.5s-6.5-4-6.5-8c0-2 1.5-3.5 3.5-3.5c1.25 0 2.25.75 3 1.75c.75-1 1.75-1.75 3-1.75c2 0 3.5 1.5 3.5 3.5c0 4-6.5 8-6.5 8ZM6.5 3A3.5 3.5 0 0 1 3 6.5M10 3a7 7 0 0 1-7 7");
}

</style>
