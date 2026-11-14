<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zcqj_pjtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:boxing-glove" /></template>
<style>
.zcqj_pjtd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 17V8.5c0-3.5 2.5-6 6-6c3.75 0 6.5 2.75 6.5 6.5v5c0 1.75-.75 3-2 3M7 9.5c-2.5 0-3.5 1.5-3.5 3c0 2 1.5 3 3.5 3M6 17h12.5v4.5H6Z");
}

</style>
