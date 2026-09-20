<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGGlQuPeQs)" class="r4i437pya"/><path class="sb40mabbb"/><path clip-rule="evenodd" class="ol12g7blg"/></g><defs><linearGradient id="SVGGlQuPeQs" x1="7.714" x2="16.143" y1="5.429" y2="18.286" gradientUnits="userSpaceOnUse"><stop class="uvhtnccri"/><stop offset=".38" class="jrfu1k1kl"/><stop offset=".74" class="ebrro4btw"/><stop offset="1" class="ffhlweo6a"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cummies-background" /></template>
<style>
.ebrro4btw {
  stop-color: var(--svg-color--f0a, #f0a);
}

.ffhlweo6a {
  stop-color: var(--svg-color--d517d1, #d517d1);
}

.ft5dv1b6b {
  fill: none;
}

.jrfu1k1kl {
  stop-color: var(--svg-color--fd00b3, #fd00b3);
}

.ol12g7blg {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("m17.355 16.725l-1.44.73l.73 1.1l-.63 1.445H13.41l.84-2h-1.3l-.805 2H9.5l4.54-11h5.01l.95 1.445zm-3.315-1.2c-.02-.115-.04-.205-.035-.255c.02-.155.035-.19.3-.32c-.23-.1-.185-.385-.13-.51c-.145.035-.475.14-.67.285c-.065-.59.425-.87.68-.94c-.06-.095-.075-.54.345-1.575c.42-1.03 1.515-1.57 2.01-1.71c.27.475.705 1.68.285 2.71c-.42 1.035-.75 1.33-.86 1.35c.14.24.305.805-.16 1.16a2.4 2.4 0 0 0-.3-.7c-.05.125-.215.355-.46.25c.105.29.095.325 0 .45c-.035.04-.11.085-.21.15c-.21.125-.515.31-.735.63a2.5 2.5 0 0 0-.06-.975");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.sb40mabbb {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.69 7.5H11l.69-2h-1.265l-3.675 9h1.305l.945-2h2.73l-.92 2.135L8.885 16h-4.15L4 14.635l3.65-9.27L9.5 4h4.19l.81 1.365z");
}

.uvhtnccri {
  stop-color: var(--svg-color--f000e1, #f000e1);
}

</style>
