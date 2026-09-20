<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGZUlXVlMJ)" class="r4i437pya"/><path class="q9uhu7b8q"/></g><defs><linearGradient id="SVGZUlXVlMJ" x1="17.714" x2="4" y1="5.429" y2="20" gradientUnits="userSpaceOnUse"><stop class="i5e06nbvn"/><stop offset=".93" class="vm5itqb0u"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ever-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i5e06nbvn {
  stop-color: var(--svg-color--f96829, #f96829);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q9uhu7b8q {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.091 4L4 10.069h9.931V20L20 13.931V4z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.vm5itqb0u {
  stop-color: var(--svg-color--6347f4, #6347f4);
}

</style>
