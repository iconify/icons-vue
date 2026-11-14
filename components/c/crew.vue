<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="as8lrbc3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:crew" /></template>
<style>
.as8lrbc3p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 6.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM6.5 21c0-5 2.5-7.5 5.5-7.5s5.5 2.5 5.5 7.5M2.5 9.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm14.5 0a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM2.5 19c0-3 1-4.5 3-4.75m16 4.75c0-3-1-4.5-3-4.75");
}

</style>
