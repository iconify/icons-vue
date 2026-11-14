<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4k-yyblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cheat-meal" /></template>
<style>
.t4k-yyblw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 10.5C4 6.5 7.5 4 12 4s8 2.5 8 6.5ZM4 17h16v1a2.5 2.5 0 0 1-2.5 2.5h-11A2.5 2.5 0 0 1 4 18Zm-1-3.25h18M10 7.5h.01m3.99 0h.01");
}

</style>
