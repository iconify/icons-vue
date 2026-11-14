<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7h0vybld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flower-heart" /></template>
<style>
.m7h0vybld {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 13.5c-5.5-3-7.5-6-6.5-8.5c1-2.25 5-2.5 6.5.25c1.5-2.75 5.5-2.5 6.5-.25c1 2.5-1 5.5-6.5 8.5Zm0 0v8m0-2c-2.5 0-5-1.5-5.5-4c2.5 0 5 1.5 5.5 4Zm0 0c2.5 0 5-1.5 5.5-4c-2.5 0-5 1.5-5.5 4Z");
}

</style>
