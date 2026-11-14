<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvwwsc7zg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:golf-trolley" /></template>
<style>
.zvwwsc7zg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 7h7v13h-7Zm7 2.5l5-5.5m-5 14h4m0 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM7 7V3.5H5M9.5 7V2.5h2");
}

</style>
