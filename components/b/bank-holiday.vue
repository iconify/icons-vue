<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gzvfg-bfy"/><path class="dnuyrrbvb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bank-holiday" /></template>
<style>
.dnuyrrbvb {
  d: path("M10 15a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm2-4.5v1m0 7v1M7.5 15h1m7 0h1m-7.75-3.25l.75.75m5.75-.75l-.75.75m-5.75 5.75l.75-.75m5.75.75l-.75-.75");
}

.gzvfg-bfy {
  d: path("M3.5 4.5h17v17h-17Zm4.5-2V6m8-3.5V6M3.5 8h17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
