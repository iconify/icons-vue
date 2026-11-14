<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a128vkvrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:electric-shock" /></template>
<style>
.a128vkvrz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.5 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm2 3.5v6.5m-3 6.5l3-6.5l3 6.5m-3-11.5l4 3m-4-3l-4-1M3 3l4 4l-2.5 1.5l4 4");
}

</style>
