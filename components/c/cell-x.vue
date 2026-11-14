<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tgxroliny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cell-x" /></template>
<style>
.tgxroliny {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.58 20.485q-.287.015-.58.015c-5 0-8.5-3.5-8.5-8.5s3-9.5 7.5-9.5c5.5 0 10.5 3 10.5 8.5q0 .314-.017.621M15.5 15.5l5 5m0-5l-5 5");
}

</style>
