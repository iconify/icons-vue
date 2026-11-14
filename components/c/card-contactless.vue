<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="emw14kl7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:card-contactless" /></template>
<style>
.emw14kl7e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8.5H13v7H2.5Zm0 2.5H13m2.622-2.521a7.5 7.5 0 0 1 0 7.042m2.428-8.333a10.25 10.25 0 0 1 0 9.624m2.428-10.915a13 13 0 0 1 0 12.206");
}

</style>
