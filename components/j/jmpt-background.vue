<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="bd0q07bkd"/><path class="g2zuki8_x"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:jmpt-background" /></template>
<style>
.bd0q07bkd {
  fill: var(--svg-color--3256f2, #3256f2);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.g2zuki8_x {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.21 7.368L14.317 4L12.42 7.368h.842v9.516a1.263 1.263 0 1 1-2.526 0v-6.147h.842L9.684 7.368L7.79 10.737h.842v6.295c0 1.642 1.275 2.968 2.846 2.968h1.044c1.57 0 2.846-1.33 2.846-2.968V7.368z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
