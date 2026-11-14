<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6720n1pv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:drysuit" /></template>
<style>
.s6720n1pv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 3h6l4 4l-1.5 2.5l-2-1.5v13h-2.75L12 13l-.75 8H8.5V8l-2 1.5L5 7Zm3 3h.01");
}

</style>
