<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qv7avab7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ampersand" /></template>
<style>
.qv7avab7r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M19 19.5L9.25 9.25c-1.5-1.5-1-4.75 1.75-4.75c2.5 0 3.25 3 1.25 4.5L8 12c-2.5 1.75-2.75 3.5-2.25 5C6.4 18.75 8 19.5 10 19.5c3 0 5.5-2 7-6");
}

</style>
