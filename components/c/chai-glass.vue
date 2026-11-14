<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8iiscdzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chai-glass" /></template>
<style>
.d8iiscdzc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 8h10l-1 12.5H8Zm.25 3h9.5M10 5.25c-.75-.75.75-1.75 0-2.75m4 2.75c-.75-.75.75-1.75 0-2.75");
}

</style>
