<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zhvq7lwot"/><path class="inggwz8bp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:contact-owner" /></template>
<style>
.inggwz8bp {
  d: path("M6.75 9a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM5.5 15.75c0-1.5 1.5-2 3.25-2s3.25.5 3.25 2M15 9h3.5m-4 10.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm3-1.25l3.75-3.75m-1.5 1.5l1.5 1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zhvq7lwot {
  d: path("M11.8 19H2.5V4h19v7.1");
}

</style>
