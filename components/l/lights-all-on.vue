<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2z07-mwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lights-all-on" /></template>
<style>
.m2z07-mwg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 16v-1.5c-1.25-1-2-2.25-2-3.75a3.75 3.75 0 0 1 7.5 0c0 1.5-.75 2.75-2 3.75V16Zm.5 3H8m7.5-3v-1.5c-1.25-1-2-2.25-2-3.75a3.75 3.75 0 0 1 7.5 0c0 1.5-.75 2.75-2 3.75V16Zm.5 3h2.5M6.75 2.75v1.5m-4 .5l.75.75m13.75-2.75v1.5m4 .5l-.75.75");
}

</style>
