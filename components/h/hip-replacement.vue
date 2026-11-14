<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zs0dl9bzl"/><path class="nttuw_2sm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hip-replacement" /></template>
<style>
.nttuw_2sm {
  d: path("M3.25 8a5.25 5.25 0 0 1 10.5 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zs0dl9bzl {
  d: path("M5.25 8a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Zm5.5 2.5L15.5 14v6.75c0 .75-.75 1-1.25.5l-1.75-6l-3-2.75");
}

</style>
