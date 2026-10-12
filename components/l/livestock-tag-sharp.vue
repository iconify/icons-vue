<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="g3nwdpojl"/><path class="s3grvx9qz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:livestock-tag-sharp" /></template>
<style>
.g3nwdpojl {
  d: path("M10.25 7.5v-4h3.5v4M5.5 9V7.5h13v6.75c0 3.75-2.75 6.25-6.5 7c-3.75-.75-6.5-3.25-6.5-7Z");
}

.s3grvx9qz {
  d: path("M10.75 11.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
