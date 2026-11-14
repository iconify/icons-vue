<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbyzuib7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fruit-basket" /></template>
<style>
.xbyzuib7z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12h18l-1.75 7c-.25 1-1 1.5-2 1.5H6.75c-1 0-1.75-.5-2-1.5Zm1.5-4a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm8 0a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Z");
}

</style>
