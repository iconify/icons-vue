<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="vzpeixe1u"/><path class="d2vmox2_d"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lpt-background" /></template>
<style>
.d2vmox2_d {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.733 4h-3.2v3.2h3.2zm0 6.4h-3.2v3.2h3.2zm-3.2 6.4h3.2V20h-3.2zm9.068-3.2H10.4v3.201h3.2zM10.4 7.2h3.2v3.2h-3.2zm9.067 3.2h-3.2v3.2h3.2z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vzpeixe1u {
  fill: var(--svg-color--00eb88, #00eb88);
  d: path("M24 0H0v24h24z");
}

</style>
