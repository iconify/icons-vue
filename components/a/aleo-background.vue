<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="b1f7l1but"/><path class="ws2r8pbwo"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:aleo-background" /></template>
<style>
.b1f7l1but {
  fill: var(--svg-color--111, #111);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.ws2r8pbwo {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.977 4h-3.685l-3.198 9.354H9.04l2.591-7.631h.938l2.59 7.631H9.042l-.602 1.723h7.303L17.416 20h2.01zM4.821 20h1.943l1.675-4.923H6.504zm.342-6.646l-.59 1.723h1.931l.59-1.723z");
}

</style>
