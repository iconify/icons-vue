<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgurlxbxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:batch-recipe" /></template>
<style>
.cgurlxbxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12.5h18c0 5-4 8.5-9 8.5s-9-3.5-9-8.5ZM3 7h17M10 7a5.5 2.75 0 1 0 11 0a5.5 2.75 0 1 0-11 0Z");
}

</style>
