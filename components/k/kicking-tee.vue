<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zw2ps2tqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:kicking-tee" /></template>
<style>
.zw2ps2tqb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 8.5a4 6.25 0 1 0 8 0a4 6.25 0 1 0-8 0Zm0 13l2.5-4h3l2.5 4Zm4.75-15.25l-1.5 4.5M11 8.25L13 9");
}

</style>
