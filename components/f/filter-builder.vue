<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwfa8ab-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:filter-builder" /></template>
<style>
.lwfa8ab-o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 3h12.5v4.5H9Zm0 6.75h12.5v4.5H9Zm0 6.75h12.5V21H9ZM7 5.25H3.5v13.5H7M3.5 12H7m7-9v4.5m0 2.25v4.5m0 2.25V21");
}

</style>
