<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtf5wqj5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:blog-author" /></template>
<style>
.vtf5wqj5l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.172 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c1.881 0 3.567.441 4.861 1.214M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm15.25 8.75l-1.5-1.5L16 18.5L15 21l2.5-1Z");
}

</style>
