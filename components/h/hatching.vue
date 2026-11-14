<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zkvmxrbeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hatching" /></template>
<style>
.zkvmxrbeb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.5 13.5l2.75 2.25l2.5-2.5l2.5 2.5l2.5-2.5l2.75.25c0 4.75-3 8-6.5 8s-6.5-3.25-6.5-8ZM6 10l3.25.5l2.5-2.25l3.25.5l2.5-2.25C15.5-.25 4 3.25 6 10Z");
}

</style>
