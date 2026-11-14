<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4zexibpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:air-compressor" /></template>
<style>
.c4zexibpb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 11h12.5a1.5 1.5 0 0 1 1.5 1.5v4a1.5 1.5 0 0 1-1.5 1.5H4a1.5 1.5 0 0 1-1.5-1.5v-4A1.5 1.5 0 0 1 4 11Zm2.5-7h7v4.5h-7ZM10 8.5V11m-4 7v3m8.5-3v3m3.5-6.5h1a2 2 0 0 1 2 2v2m-1 0h2v3h-2Z");
}

</style>
