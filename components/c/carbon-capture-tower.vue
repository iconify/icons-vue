<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aieiarnzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:carbon-capture-tower" /></template>
<style>
.aieiarnzd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14 2.5h4.5l1.5 19h-7.5ZM13.5 8H19m-5.75 5h6M3 18h7m-2.75-2.75L10 18l-2.75 2.75");
}

</style>
