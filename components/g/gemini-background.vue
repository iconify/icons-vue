<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="loqgjxbtb"/><path class="zyuwx6bqy"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gemini-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.loqgjxbtb {
  fill: var(--svg-color--00dcfa, #00dcfa);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.zyuwx6bqy {
  fill: var(--svg-color--000, #000);
  d: path("M10.174 13.824h3.653v-3.648h-3.653zm-4.866.002h3.606v-3.605a4.27 4.27 0 0 0-2.399 1.212a4.28 4.28 0 0 0-1.207 2.393m3.606 1.259H5.308a4.28 4.28 0 0 0 1.208 2.393a4.25 4.25 0 0 0 3.014 1.257h.028c1.173 0 2.24-.482 3.015-1.257a4.3 4.3 0 0 0 1.207-2.39H8.914zm9.78-4.91h-3.606v3.604a4.27 4.27 0 0 0 2.398-1.213a4.3 4.3 0 0 0 1.207-2.39m-.001-1.263a4.28 4.28 0 0 0-1.207-2.39a4.25 4.25 0 0 0-3.015-1.258h-.028c-1.173 0-2.24.482-3.014 1.257a4.3 4.3 0 0 0-1.208 2.39zm-3.639 6.145a5.54 5.54 0 0 1-1.59 3.315A5.5 5.5 0 0 1 9.557 20H9.53a5.5 5.5 0 0 1-3.905-1.628a5.535 5.535 0 0 1 0-7.832a5.5 5.5 0 0 1 3.321-1.597a5.54 5.54 0 0 1 1.591-3.315A5.5 5.5 0 0 1 14.443 4h.028c1.52 0 2.903.623 3.905 1.628a5.536 5.536 0 0 1 0 7.832a5.52 5.52 0 0 1-3.322 1.597");
}

</style>
