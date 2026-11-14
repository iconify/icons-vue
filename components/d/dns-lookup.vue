<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ky814dbkv"/><path class="y6b7anhms"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dns-lookup" /></template>
<style>
.ky814dbkv {
  d: path("M2.5 7.75a5.25 5.25 0 1 0 10.5 0a5.25 5.25 0 1 0-10.5 0Zm11 5.25h8v8.5h-8Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y6b7anhms {
  d: path("M5.75 7.75a2 5.25 0 1 0 4 0a2 5.25 0 1 0-4 0Zm-3.25 0H13m.5 9.5h8M5 16v2.5h5.5m-1.75-1.75l1.75 1.75l-1.75 1.75");
}

</style>
