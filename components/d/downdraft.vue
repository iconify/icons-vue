<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hd-4zbcml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:downdraft" /></template>
<style>
.hd-4zbcml {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 11.75h8.5a2.5 2.5 0 0 0 0-5a4.25 4.25 0 0 0-8.5 0a2.5 2.5 0 0 0 0 5ZM12 14.5v7m-3.75-3.75L12 21.5l3.75-3.75");
}

</style>
