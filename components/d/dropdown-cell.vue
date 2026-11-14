<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tce7z28xi"/><path class="pbmrk3btd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dropdown-cell" /></template>
<style>
.pbmrk3btd {
  d: path("m16.75 11.25l1.5 1.5l1.5-1.5M6 12h5");
}

.tce7z28xi {
  d: path("M2.5 7h19v10h-19ZM15 7v10");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
