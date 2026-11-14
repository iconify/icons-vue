<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9pt3hj0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hotfix" /></template>
<style>
.e9pt3hj0n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.75 16.25l5.75-5.75a4.5 4.5 0 0 1 6-6l-4 4a1.5 1.5 0 0 0 2 2l4-4a4.5 4.5 0 0 1-6 6l-5.75 5.75a1.5 1.5 0 0 1-2-2ZM19 14.5l-3.5 4H18l-1 3l3.75-4.25H18.5Z");
}

</style>
