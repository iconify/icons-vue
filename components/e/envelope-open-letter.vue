<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fni79ccee"/><path class="dlpk0pdin"/><path class="gbf6dccar"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:envelope-open-letter" /></template>
<style>
.dlpk0pdin {
  d: path("m3.5 10.5l8.5 5l8.5-5");
}

.fni79ccee {
  d: path("M6.5 7.75L3 10v8a2 2 0 0 0 2 2h14a2 2 0 0 0 2-2v-8l-3.5-2.25");
}

.gbf6dccar {
  d: path("M6.5 12.25V4.5a1 1 0 0 1 1-1h9a1 1 0 0 1 1 1v7.75M9.5 7h5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
