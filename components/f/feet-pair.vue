<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g70bs-b2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:feet-pair" /></template>
<style>
.g70bs-b2g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 11.5c0-3.5 6.5-4 6.5 0L9.5 18A2.75 2.75 0 0 1 4 18Zm17 0c0-3.5-6.5-4-6.5 0l.5 6.5a2.75 2.75 0 0 0 5.5 0Zm-13-6.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0ZM5 5.5h.01M14 4.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm5 .75h.01");
}

</style>
