<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j51v7yb9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:copy-editor" /></template>
<style>
.j51v7yb9r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 2.5h11.5v19H3ZM6 8h5.5M6 12h5.5M6 16h3.5m8-11.5a1.5 1.5 0 0 1 3 0v13l-1.5 3l-1.5-3Z");
}

</style>
