<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqixx-g7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:array-list" /></template>
<style>
.fqixx-g7a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.625 3h2.75A2.625 2.625 0 0 1 16 5.625v12.75A2.625 2.625 0 0 1 13.375 21h-2.75A2.625 2.625 0 0 1 8 18.375V5.625A2.625 2.625 0 0 1 10.625 3M8 9h8m-8 6h8M5 3H3.5v18H5M19 3h1.5v18H19");
}

</style>
