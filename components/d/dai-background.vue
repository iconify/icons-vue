<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="u77zwebfs"/><path clip-rule="evenodd" class="pcy5wdbmy"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dai-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.pcy5wdbmy {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M11.711 4.774H5.548V9.42H4v2.065h1.548v1.032H4v2.065h1.548v4.645h6.163a7.265 7.265 0 0 0 6.782-4.645H20v-2.065h-1.053a7 7 0 0 0 0-1.032H20V9.419h-1.507a7.27 7.27 0 0 0-6.782-4.645m5.161 7.742a5 5 0 0 0 0-1.032h-9.26v1.032h9.266zm-9.26 2.065v2.58h3.985c1.962 0 3.68-1.037 4.594-2.58zm0-5.162h8.584a5.33 5.33 0 0 0-4.593-2.58h-3.99z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.u77zwebfs {
  fill: var(--svg-color--fdc134, #fdc134);
  d: path("M24 0H0v24h24z");
}

</style>
