<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ba2k07rbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cloud-tops" /></template>
<style>
.ba2k07rbu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 21h13a2.75 2.75 0 0 0 .5-5.5a4 4 0 0 0-7.5-1.5A3.5 3.5 0 0 0 5 15.75A2.75 2.75 0 0 0 5.5 21Zm3-8.75V3M6 5.5L8.5 3L11 5.5M5.5 3h6");
}

</style>
