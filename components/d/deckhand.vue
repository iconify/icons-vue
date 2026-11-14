<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vn-4t1-8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:deckhand" /></template>
<style>
.vn-4t1-8j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.572 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c1.72 0 3.276.368 4.519 1.023M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0ZM19 18.5a1.5 1.5 0 0 0-3 0a3 3 0 0 0 6 0");
}

</style>
