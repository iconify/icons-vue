<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nxe97hb_a"/><path class="c_wtobcpx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:code-minimap" /></template>
<style>
.c_wtobcpx {
  fill: currentColor;
  d: path("M17.5 5h4v4h-4Z");
}

.nxe97hb_a {
  d: path("M2.5 2.5h12v19h-12Zm3 4.5h6m-6 4h4m-4 4h6m6-12.5h4v19h-4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
