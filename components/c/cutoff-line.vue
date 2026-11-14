<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i9-z-rd-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cutoff-line" /></template>
<style>
.i9-z-rd-x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 7.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm0 9a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm4-7.5L14 15m-6.75 0L14 9m2.5 3H18m2.75 0h1");
}

</style>
