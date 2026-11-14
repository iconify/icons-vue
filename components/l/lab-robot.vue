<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sek9p462w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lab-robot" /></template>
<style>
.sek9p462w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 20h7m-3.5 0L8.75 8.5M7 6.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm4 0h5.5V10m-2 2.75V10h4v2.75M13 15.5h7.5V20H13Z");
}

</style>
