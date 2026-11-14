<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8rpdbsyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:duckling" /></template>
<style>
.z8rpdbsyc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 9.5c2 1.5 4.5 1.5 8 1c-1-2-.5-6.5 3-7c2.25-.25 3.5 1.25 3.5 2.75l2.5 1l-2.75 1.25c-.25.75-.5 1.5-1 2.25c2.5.25 3.5 1.75 3 3.25c-1 3-3.75 4-7.75 4c-5 0-8-2.5-8.5-8.5Zm0 11.25h17M14.75 6.5h.01");
}

</style>
