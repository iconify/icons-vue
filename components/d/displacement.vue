<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4aoo3b6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:displacement" /></template>
<style>
.w4aoo3b6n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 19a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM17 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM8.5 15.5l7-7m-4 0h4v4");
}

</style>
