<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhi8-xk3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:genre-folk" /></template>
<style>
.rhi8-xk3j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 16a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0ZM10 2.5h4v3h-4Zm2 3v14m-2-2h4");
}

</style>
