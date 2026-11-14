<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awbtfu2dd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:assignee" /></template>
<style>
.awbtfu2dd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0ZM3 20.5c0-3.75 3.25-6 7.5-6c1.187 0 2.295.175 3.277.51M14.75 18l2 2L21 15.75");
}

</style>
