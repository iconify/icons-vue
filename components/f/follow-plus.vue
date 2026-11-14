<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afjilgb1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:follow-plus" /></template>
<style>
.afjilgb1n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 7.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Zm-3 14c0-4 3.25-6.5 7.5-6.5c.758 0 1.485.08 2.167.233M18 15v6m-3-3h6");
}

</style>
