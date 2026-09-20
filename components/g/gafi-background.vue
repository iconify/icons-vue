<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="c8uakjidl"/><path class="v9iejj-fk"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gafi-background" /></template>
<style>
.c8uakjidl {
  fill: var(--svg-color--72f34b, #72f34b);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.v9iejj-fk {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.263 8.632A1.263 1.263 0 0 0 4 9.895v4.21a1.263 1.263 0 0 0 1.263 1.263h5.474A1.263 1.263 0 0 0 12 14.105v-1.684a1.263 1.263 0 0 0-1.263-1.263h-3.79v1.684h2.948v.421h-3.79v-2.526H12V8.632zm9.263 1.684h5.053V9.053h-5.474a.84.84 0 0 0-.842.842v5.053h1.263v-2.106h5.053V11.58h-5.053zm.421 4.884a.17.17 0 0 1-.168.168h-1.768a.17.17 0 0 1-.169-.168V9.895a1.263 1.263 0 0 1 1.263-1.263h5.727c.092 0 .168.075.168.168v1.768a.17.17 0 0 1-.168.169h-4.885v.42h4.885a.17.17 0 0 1 .168.17v1.768a.17.17 0 0 1-.168.168h-4.885z");
}

</style>
