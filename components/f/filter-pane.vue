<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i8j7esozv"/><path class="z1k0ex5ae"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:filter-pane" /></template>
<style>
.i8j7esozv {
  d: path("M2.5 3.5h19v17h-19Zm8 0v17M5 8h3m-3 4h3m-3 4h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z1k0ex5ae {
  fill: currentColor;
  d: path("M5.25 8a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm1.25 4a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm-2 4a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

</style>
