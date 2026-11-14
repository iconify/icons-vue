<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hc993nbmz"/><path class="p-bfwnbwt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:git-tag-protected" /></template>
<style>
.hc993nbmz {
  d: path("M11.2 16H8L2.5 9.5L8 3h12v7.4M8 9.5h.01m5.99 7h8V22h-8Z");
}

.p-bfwnbwt {
  d: path("M15.75 16.5V15a2.25 2.25 0 0 1 4.5 0v1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
