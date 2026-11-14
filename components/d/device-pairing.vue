<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="edytnuw3p"/><path class="bq_6neist"/><path class="lci6zbgiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:device-pairing" /></template>
<style>
.bq_6neist {
  d: path("m15.5 8.5l2 2l2-2m-9 9h-4v-4");
}

.edytnuw3p {
  d: path("M2.5 2.5h8v8h-8Zm11 11h8v8h-8Zm0-7h4v4");
}

.lci6zbgiv {
  d: path("m4.5 15.5l2-2l2 2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
