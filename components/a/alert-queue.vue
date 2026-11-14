<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqlpu0b9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:alert-queue" /></template>
<style>
.tqlpu0b9h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 4h17.5M3 9.5h13.2m2.6 0h1.7M3 15h7m7.5-2l4.5 8.5h-9Zm0 3.75v.75m0 2.25h.01");
}

</style>
