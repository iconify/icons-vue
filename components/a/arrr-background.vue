<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGKJ1Xgc7q)" class="r4i437pya"/><path class="s4uccybvj"/></g><defs><linearGradient id="SVGKJ1Xgc7q" x1="5.388" x2="18.714" y1="5.286" y2="19.518" gradientUnits="userSpaceOnUse"><stop class="gvrvndxaq"/><stop offset="1" class="jezxccrcr"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:arrr-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gvrvndxaq {
  stop-color: var(--svg-color--bf9b41, #bf9b41);
}

.jezxccrcr {
  stop-color: var(--svg-color--e2c97e, #e2c97e);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.s4uccybvj {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.286 7.429A3.43 3.43 0 0 1 7.714 4h8.572a3.43 3.43 0 0 1 2.143.754l-4.086 2.103H8.857A1.143 1.143 0 0 0 7.714 8v2.274l-3.428 1.772zm0 8.074V20h2a1.43 1.43 0 0 0 1.428-1.429V16h8.572a3.43 3.43 0 0 0 3.428-3.429V7.55l-3.428 1.77V12a1.144 1.144 0 0 1-1.143 1.143h-6.28z");
}

</style>
