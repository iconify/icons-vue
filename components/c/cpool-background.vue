<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path fill="url(#SVGAQyQRvry)" class="eruge04cp"/><path class="j2tb0hbsf"/><path fill="url(#SVGAQyQRvry)" class="brful42hh"/></g><defs><linearGradient id="SVGAQyQRvry" x1="13.271" x2="11.671" y1="4.453" y2="19.319" gradientUnits="userSpaceOnUse"><stop class="b8zi92bls"/><stop offset=".44" class="mzq8igbga"/><stop offset=".65" class="cu0mqembg"/><stop offset=".82" class="e9h66oyth"/><stop offset="1" class="hd3om9x-n"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cpool-background" /></template>
<style>
.b8zi92bls {
  stop-color: var(--svg-color--23b77f, #23b77f);
}

.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.brful42hh {
  d: path("M13.271 4a8 8 0 0 0 0 16z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.cu0mqembg {
  stop-color: var(--svg-color--396cc6, #396cc6);
}

.e9h66oyth {
  stop-color: var(--svg-color--5aa3ea, #5aa3ea);
}

.eruge04cp {
  d: path("M13.271 4a8 8 0 0 0 0 16z");
}

.ft5dv1b6b {
  fill: none;
}

.hd3om9x-n {
  stop-color: var(--svg-color--92f5ea, #92f5ea);
}

.j2tb0hbsf {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.5 8.342a3.657 3.657 0 1 0 3.217 5.395l2.012 1.097a5.943 5.943 0 1 1 0-5.669l-2.012 1.097a3.66 3.66 0 0 0-3.218-1.92");
}

.mzq8igbga {
  stop-color: var(--svg-color--2857b3, #2857b3);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
