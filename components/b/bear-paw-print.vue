<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2s8slboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bear-paw-print" /></template>
<style>
.f2s8slboi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 16a6.5 5 0 1 0 13 0a6.5 5 0 1 0-13 0Zm-3-6a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm2.75-4.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm5.25-2a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm5.25 2a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM18.5 10a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

</style>
