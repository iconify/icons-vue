<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="n22k62bnm"/><path clip-rule="evenodd" class="u89_i2b8w"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:aht-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.n22k62bnm {
  fill: var(--svg-color--30bfbd, #30bfbd);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.u89_i2b8w {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M17.2 8.2h-.4v1.6h.4zm-7.2.4h-.8v7.2h.8v-2.4a1.6 1.6 0 0 1 3.2 0v2.4h.8v-2.4a2.4 2.4 0 0 0-4-1.788zm-3.6 7.2c.616 0 1.176-.232 1.6-.612v.612h.8v-2.4a2.4 2.4 0 1 0-2.4 2.4m0-.8a1.6 1.6 0 1 0 0-3.2a1.6 1.6 0 0 0 0 3.2m10.4.8c.616 0 1.176-.232 1.6-.612v.612h.8v-2.4a2.4 2.4 0 1 0-2.4 2.4m0-.8a1.6 1.6 0 1 0 0-3.2a1.6 1.6 0 0 0 0 3.2m-2.472-6.096l-.316.316l1.26 1.264l.32-.32zM20 9.2l-.316-.316l-1.26 1.264l.316.32z");
}

</style>
