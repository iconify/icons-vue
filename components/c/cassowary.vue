<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-36dbbij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cassowary" /></template>
<style>
.l-36dbbij {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 14.5c-1.5-4.5 2-7 6-6c2 .5 3-.5 3-2L14.5 3L17 4.75l3.5 1.75l-3.5 1q-.75 2.25 0 4.5c0 4-4 5-8 4.75c-2.5-.25-4-1.25-5-2.25Zm5.5 2.25l1 4.25m3-4.5L13 21");
}

</style>
