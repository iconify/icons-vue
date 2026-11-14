<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r38fteblr"/><path class="qy4jaeb3a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dept-household-sign" /></template>
<style>
.qy4jaeb3a {
  d: path("m8.5 14.5l3.5-3.25l3.5 3.25V18h-7Z");
}

.r38fteblr {
  d: path("M3 8.5h18v12H3ZM7 3v5.5M17 3v5.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
