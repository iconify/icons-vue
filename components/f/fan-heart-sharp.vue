<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6varsbbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fan-heart-sharp" /></template>
<style>
.c6varsbbm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 20.25h-.525l-.375-.3c-2.7-2.2-5.85-4.85-5.85-8.45c0-2.2 1.65-3.9 3.75-3.9h1.821L9.5 9.25l1.179-1.65H12.5c2.1 0 3.75 1.7 3.75 3.9c0 3.6-3.15 6.25-5.85 8.45l-.375.3zm5.75-17.5a6 6 0 0 1 6 6M15 6l3.318-.318L18 9");
}

</style>
