<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r4ql976jw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:autumn-tree" /></template>
<style>
.r4ql976jw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 15.5c-3 0-3.5-4.5-1-6c-.5-4 3-7 6-6.5c3-.5 6.5 2.5 6 6.5c2.5 1.5 2 6-1 6Zm5 0v6m-8.5 0c0-2 1.5-3.25 3.5-3.25c0 2-1.5 3.25-3.5 3.25Zm17 0c0-2-1.5-3.25-3.5-3.25c0 2 1.5 3.25 3.5 3.25Z");
}

</style>
