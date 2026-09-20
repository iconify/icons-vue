<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGyF8iIm2v)" class="r4i437pya"/><path class="vy18cdp4c"/></g><defs><linearGradient id="SVGyF8iIm2v" x1="6.977" x2="23.471" y1="6.774" y2="25.72" gradientUnits="userSpaceOnUse"><stop class="iec-__bqf"/><stop offset="1" class="p1we3jffn"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:fet-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.iec-__bqf {
  stop-color: var(--svg-color--1a1e21, #1a1e21);
}

.p1we3jffn {
  stop-color: var(--svg-color--06060a, #06060a);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.vy18cdp4c {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 4h2v2H4zm5 0h2v2H9zm0 5h2v2H9zm5-5h2v2h-2zm5 .5h1v1h-1zm0 5h1v1h-1zm-4.5 0h1v1h-1zm0 5h1v1h-1zm-5 0h1v1h-1zm-5 4.5h1v1h-1zm5 0h1v1h-1zm5 0h1v1h-1zm4.5 0h1v1h-1zm0-4.5h1v1h-1zM4 9h2v2H4zm0 5h2v2H4z");
}

</style>
