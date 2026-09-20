<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="iqz_gpb0k"/><path class="et5-jul7k"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:abstract-background" /></template>
<style>
.et5-jul7k {
  fill: var(--svg-color--fff, #fff);
  d: path("m14.532 14.467l3.209 3.179l-1.506 1.49l-3.208-3.177a1.45 1.45 0 0 0-1.029-.421c-.39 0-.752.148-1.028.421l-3.208 3.179l-1.506-1.492l3.208-3.179zm.535-.916l4.383 1.162l.55-2.04l-4.382-1.16a1.44 1.44 0 0 1-1.028-1.765l1.173-4.34l-2.058-.546l-1.174 4.341l2.534 4.346zm-6.134 0L4.55 14.713L4 12.673l4.382-1.16A1.44 1.44 0 0 0 9.41 9.747l-1.173-4.34l2.058-.546l1.173 4.341l-2.533 4.346z");
}

.ft5dv1b6b {
  fill: none;
}

.iqz_gpb0k {
  fill: var(--svg-color--054729, #054729);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
