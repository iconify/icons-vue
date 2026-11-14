<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ag9e-ibqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:browser-extension-risk" /></template>
<style>
.ag9e-ibqo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 10h2.5a2.75 2.75 0 0 1 5.5 0h2.5v2.5a2.75 2.75 0 0 1 0 5.5v2.5H3Zm16.5-7v5.5m0 3.5h.01");
}

</style>
