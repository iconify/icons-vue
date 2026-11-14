<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmog1hbxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:briefcase-check" /></template>
<style>
.dmog1hbxg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.3 18.5H2.5V6h18v6.3M8 6V4.5A1.5 1.5 0 0 1 9.5 3h4A1.5 1.5 0 0 1 15 4.5V6m-.25 12l2 2L21 15.75");
}

</style>
