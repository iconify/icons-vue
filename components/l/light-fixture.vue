<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dekqqclrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:light-fixture" /></template>
<style>
.dekqqclrv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 4.5h6m-3 0V9m-7 8c0-4.5 3-8 7-8s7 3.5 7 8Zm4.5 0a2.5 2.5 0 0 0 5 0");
}

</style>
