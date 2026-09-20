<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="qj4e8rbuh"/><path class="y3zejhnax"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kaia-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qj4e8rbuh {
  fill: var(--svg-color--bff009, #bff009);
  d: path("M24 0H0v24h24z");
}

.y3zejhnax {
  fill: var(--svg-color--000, #000);
  d: path("M12.144 7.972a1.16 1.16 0 0 1 1.162-1.157h2.08V4h-2.08c-2.204 0-3.99 1.779-3.99 3.972c0 .572.122 1.116.341 1.607c-1.711.72-2.848 2.25-3.112 4.186c-.31 2.126.546 4.42 2.41 5.527c1.663 1.042 4.263.974 5.668-.473v.96h2.894V9.13h-4.21c-.64 0-1.164-.52-1.164-1.157m2.543 3.973v2.673A2.68 2.68 0 0 1 12 17.292a2.68 2.68 0 0 1-2.685-2.674A2.68 2.68 0 0 1 12 11.945z");
}

</style>
