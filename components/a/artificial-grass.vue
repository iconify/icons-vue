<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vyx-ai0xo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:artificial-grass" /></template>
<style>
.vyx-ai0xo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13h19v5.5h-19ZM4 13l2-7.5L8 13l2-7.5l2 7.5l2-7.5l2 7.5l2-7.5l2 7.5");
}

</style>
