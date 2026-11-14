<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jb3403bsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:column-corinthian" /></template>
<style>
.jb3403bsd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 6.5a1.75 1.75 0 0 1 0-3.5h16.5a1.75 1.75 0 0 1 0 3.5M7.5 3v15m9-15v15m-11 0h13v3.5h-13ZM12 9.5V15");
}

</style>
