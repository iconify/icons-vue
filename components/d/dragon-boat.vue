<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wv-a74btb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dragon-boat" /></template>
<style>
.wv-a74btb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14.5H19L17 19H6.5c-2 0-3.25-2-4-4.5Zm13.5 0v-4C16 8.25 17.25 7 19.25 7h2.25l-1 3h-1.75v4.5m-1.5-7.25l-1-2.5M2.5 14.5c0-2 .5-3.5 2-4");
}

</style>
