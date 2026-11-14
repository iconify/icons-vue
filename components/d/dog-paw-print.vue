<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4bbdabks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dog-paw-print" /></template>
<style>
.n4bbdabks {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12c2.5 0 6 4 6 6.5c0 2-1.5 2.5-3 2.5c-1 0-2-.5-3-.5s-2 .5-3 .5c-1.5 0-3-.5-3-2.5C6 16 9.5 12 12 12ZM2 12a2 2.5 0 1 0 4 0a2 2.5 0 1 0-4 0Zm4.5-6a2 2.75 0 1 0 4 0a2 2.75 0 1 0-4 0Zm7 0a2 2.75 0 1 0 4 0a2 2.75 0 1 0-4 0Zm4.5 6a2 2.5 0 1 0 4 0a2 2.5 0 1 0-4 0Z");
}

</style>
