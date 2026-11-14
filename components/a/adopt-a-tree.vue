<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="stm4lebns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:adopt-a-tree" /></template>
<style>
.stm4lebns {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 8.25a6.25 6.25 0 1 0 12.5 0a6.25 6.25 0 1 0-12.5 0Zm6.25 6.25v7m7.5 0l-3-3a2 2 0 0 1 3-2.5a2 2 0 0 1 3 2.5Z");
}

</style>
