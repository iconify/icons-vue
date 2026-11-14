<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zcps4wp4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bamboo-material" /></template>
<style>
.zcps4wp4k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 3h4v18.5H5Zm0 4.5h4m-4 4.75h4M5 17h4m0-9.5c2.5-3 6.5-4.5 10.5-4c-2 3.5-6 5-10.5 4Zm0 4.75c3-.75 7-.25 10.5 2.25c-4 1-7.5 0-10.5-2.25Z");
}

</style>
