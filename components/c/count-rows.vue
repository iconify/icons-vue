<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cyz0kqbnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:count-rows" /></template>
<style>
.cyz0kqbnb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4h9v4h-9Zm0 6h9v4h-9Zm0 6h9v4h-9Zm14-1.5v7m3-7v7m-5-5h7m-7 3h7");
}

</style>
