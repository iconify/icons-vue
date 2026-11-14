<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h_0h-mbjy"/><path class="ebay9-b0m"/><path class="ur0npetif"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:card-online-payments" /></template>
<style>
.ebay9-b0m {
  d: path("M14.75 18a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Zm0 0h6.5");
}

.h_0h-mbjy {
  d: path("M11.9 19H2.5V5h19v8.1m-19-3.6h19m-19 0h19M6 15h2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ur0npetif {
  d: path("M16.75 18a1.25 3.25 0 1 0 2.5 0a1.25 3.25 0 1 0-2.5 0Z");
}

</style>
