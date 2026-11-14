<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vcyc4b3ql"/><path class="l9lkd3vvh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dependency-search" /></template>
<style>
.l9lkd3vvh {
  d: path("m5.25 13.5l2 2l2-2m6 4a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm4 1.75L21 21");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vcyc4b3ql {
  d: path("M2.5 3H12v5.5H2.5Zm0 12.5H12V21H2.5Zm4.75-7v7");
}

</style>
