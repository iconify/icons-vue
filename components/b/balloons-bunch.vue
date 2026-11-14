<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awe7g9bez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:balloons-bunch" /></template>
<style>
.awe7g9bez {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 5.75a3 3.5 0 1 0 6 0a3 3.5 0 1 0-6 0ZM3.75 11a3 3.5 0 1 0 6 0a3 3.5 0 1 0-6 0Zm10.5 0a3 3.5 0 1 0 6 0a3 3.5 0 1 0-6 0Zm-7.5 3.5L12 21m5.25-6.5L12 21m0-11.75V21");
}

</style>
