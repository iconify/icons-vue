<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytdirnbwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fifo-fefo" /></template>
<style>
.ytdirnbwg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4.5H7v6H2.5Zm7.25 0h4.5v6h-4.5Zm7.25 0h4.5v6H17ZM21.5 17h-19m3-3l-3 3l3 3");
}

</style>
