<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="m917_8hmn"/><path clip-rule="evenodd" class="qrf34zpwc"/><path class="m2fr7z63b"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:id-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m2fr7z63b {
  fill: var(--svg-color--fff, #fff);
  d: path("M13 10.26c0-.7.565-1.26 1.26-1.26h.48c.7 0 1.26.565 1.26 1.26v.48c0 .7-.565 1.26-1.26 1.26h-.48A1.26 1.26 0 0 1 13 10.74zm0 4.5c0-.7.565-1.26 1.26-1.26h.48c.7 0 1.26.565 1.26 1.26v.48c0 .7-.565 1.26-1.26 1.26h-.48A1.26 1.26 0 0 1 13 15.24z");
}

.m917_8hmn {
  fill: var(--svg-color--1aed9e, #1aed9e);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qrf34zpwc {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M9.22 4A4.76 4.76 0 0 0 4.5 8.8v6.4c0 2.65 2.11 4.8 4.72 4.8h5.56c2.61 0 4.72-2.15 4.72-4.8V8.8c0-2.65-2.11-4.8-4.72-4.8zm-.03 2C7.705 6 6.5 7.285 6.5 8.875v6.25C6.5 16.715 7.705 18 9.19 18h5.62c1.485 0 2.69-1.285 2.69-2.875v-6.25C17.5 7.285 16.295 6 14.81 6z");
}

</style>
