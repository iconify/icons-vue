<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sysz2t14j"/><path class="ixxgfxsrv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:baseball-diamond" /></template>
<style>
.ixxgfxsrv {
  fill: currentColor;
  d: path("m12 2l1.75 1.75L12 5.5l-1.75-1.75Zm8.25 8.25L22 12l-1.75 1.75L18.5 12Zm-16.5 0L5.5 12l-1.75 1.75L2 12ZM10.5 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.sysz2t14j {
  d: path("m12 3.5l8.5 8.5l-8.5 8.5L3.5 12Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
