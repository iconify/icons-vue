<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="edzhdc2nk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cloven-hoof-print" /></template>
<style>
.edzhdc2nk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 3.5c-4 .5-6 5.5-6 10.5c0 4 2 6.5 4.25 6.5c1.25 0 1.75-1 1.75-2.5Zm3 0c4 .5 6 5.5 6 10.5c0 4-2 6.5-4.25 6.5c-1.25 0-1.75-1-1.75-2.5Z");
}

</style>
