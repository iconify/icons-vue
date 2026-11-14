<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dwgw5dbul"/><path class="fd489bixb"/><path class="utt68dznl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:butterfly-roof" /></template>
<style>
.dwgw5dbul {
  d: path("M2.5 4.75L12 9.5l9.5-4.75");
}

.fd489bixb {
  d: path("M5 6v14.5h14V6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.utt68dznl {
  d: path("M10 14.5h4v6h-4Z");
}

</style>
