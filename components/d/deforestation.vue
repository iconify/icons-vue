<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ctfuc96bg"/><path class="bm7getb6a"/><path class="wognytb3u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:deforestation" /></template>
<style>
.bm7getb6a {
  d: path("M5 12.5V19l-1 2h16l-1-2v-6.5");
}

.ctfuc96bg {
  d: path("M5 12.5a7 3.5 0 1 0 14 0a7 3.5 0 1 0-14 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wognytb3u {
  d: path("M9.5 12.5a2.5 1.25 0 1 0 5 0a2.5 1.25 0 1 0-5 0ZM14 9.25V5.5h3V10m-1.5-4.5l4.5-3");
}

</style>
