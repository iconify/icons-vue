<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u90jitbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:campfire-allowed" /></template>
<style>
.u90jitbsv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 2.5c3 3.5 4.5 6 4.5 8.5a4.5 4.5 0 0 1-9 0C5.5 8.5 7 6 10 2.5Zm-7 19q0-3.25 3-3.25t3 3.25Zm11.285 0H9q0-2.746 2.141-3.172M14.75 18l2 2L21 15.75");
}

</style>
