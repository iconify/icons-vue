<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uyv7oe86r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:adult-traveler" /></template>
<style>
.uyv7oe86r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 7a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Zm-4 14.5V20a5 5 0 0 1 5-5h7a5 5 0 0 1 5 5v1.5");
}

</style>
