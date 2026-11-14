<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="psybxqb0b"/><path class="z0a9g6b9a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:account-fee-waived" /></template>
<style>
.psybxqb0b {
  d: path("M5.751 14.251L3 11.5V3h8.5l2.758 2.758m3.96 3.96L21 12.5L12.5 21l-2.789-2.789");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z0a9g6b9a {
  d: path("M5.75 7.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm8.72 6.218c.443.345.752.817.78 1.532c-.11.85-1.01 1.56-2.25 1.5a3.1 3.1 0 0 1-1.289-.19M13 16.5V18m-9.5 2.5l17-17");
}

</style>
