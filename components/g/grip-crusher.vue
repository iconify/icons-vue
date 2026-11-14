<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-rcj0n6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:grip-crusher" /></template>
<style>
.c-rcj0n6x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm0 0l-3 8m7-8l3 8m-11.797-.665l3.746 1.4l-3.152 8.43l-3.746-1.4Zm9.848 1.4l3.746-1.4l3.152 8.43l-3.746 1.4ZM7.75 11l2-2.25L12 13l2.25-4.25l2 2.25");
}

</style>
