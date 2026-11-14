<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zu9cy6r5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:key-hierarchy" /></template>
<style>
.zu9cy6r5b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 3h7v5h-7ZM3 16h6v5H3Zm12 0h6v5h-6Zm-3-8v4m-6 4v-2.5A1.5 1.5 0 0 1 7.5 12h9a1.5 1.5 0 0 1 1.5 1.5V16");
}

</style>
