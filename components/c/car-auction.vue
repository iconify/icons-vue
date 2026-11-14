<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2q5vtbrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:car-auction" /></template>
<style>
.g2q5vtbrn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.419 12.954L8.197 6.732l3.535-3.535l7.071 7.071l-2.687 2.687M3 19l8.75-8.75M14.5 20.5v-2.25l1.5-2.5h4.5l1.5 2.5v2.25Zm0-2.25H22");
}

</style>
