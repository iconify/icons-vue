<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l96k7ac7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:earthquake-assembly" /></template>
<style>
.l96k7ac7b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-2 8.75c0-2.5 1.75-4 4-4s4 1.5 4 4M2.5 19a9.5 2.5 0 1 0 19 0a9.5 2.5 0 1 0-19 0ZM5 5.5L2.75 8L5 10.5L2.75 13M19 5.5L21.25 8L19 10.5l2.25 2.5");
}

</style>
