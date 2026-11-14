<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqyu21j9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hair-mousse" /></template>
<style>
.xqyu21j9p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 13h13v8.5h-13Zm3-2.75h7V13h-7Zm-2 0a2.75 2.75 0 0 1 2-4.75a3.5 3.5 0 0 1 7 0a2.75 2.75 0 0 1 2 4.75Z");
}

</style>
