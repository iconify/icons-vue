<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG8jHbue8h)" class="r4i437pya"/><path class="tyudr9bzl"/></g><defs><linearGradient id="SVG8jHbue8h" x1="12" x2="12" y1="4.267" y2="19.733" gradientUnits="userSpaceOnUse"><stop class="ufqgwyb2e"/><stop offset="1" class="h1e19bxct"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:htm-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h1e19bxct {
  stop-color: var(--svg-color--33cbf0, #33cbf0);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.tyudr9bzl {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.123 8.027c-1.014-1.158-.614-2.987-.283-3.76C5.323 4.459 4 5.472 4 8.027c0 2.89 3.253 4.192 4.672 5.781c1.419 1.59 1.84 5.925 3.253 5.925c1.42 0 2.07-4.736 3.403-5.925C16.458 12.795 20 10.768 20 8.027c0-2.198-1.227-3.424-1.84-3.76c1.019 1.504.283 2.89-.565 3.76c-2.832 3.178-5.099 2.026-5.664 4.768c-.283-2.747-4.534-3.323-5.808-4.768");
}

.ufqgwyb2e {
  stop-color: var(--svg-color--64eab7, #64eab7);
}

</style>
