<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGaAZq0BwY)" class="r4i437pya"/><path clip-rule="evenodd" class="h0a2x_u8i"/></g><defs><linearGradient id="SVGaAZq0BwY" x1="6.697" x2="17.983" y1="20" y2="5.891" gradientUnits="userSpaceOnUse"><stop class="dfpk2nbcd"/><stop offset=".78" class="z5ro-b9uf"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:idex-background" /></template>
<style>
.dfpk2nbcd {
  stop-color: var(--svg-color--9722ad, #9722ad);
}

.ft5dv1b6b {
  fill: none;
}

.h0a2x_u8i {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M5.737 4h12.457L20 6.303l-4.423 5.743L20 17.749L18.217 20H5.737L4 17.749l4.394-5.703L4 6.303zm.046.794L17.21 19.423H5.874l-.868-1.132h8.52c.114 0 .183-.137.114-.228L4.554 6.33L5.79 4.79zm4.411 9.555l1.766 2.222H9.263a.413.413 0 0 1-.414-.456a.4.4 0 0 1 .088-.212zm5.057-2.738l-1.497-1.88l1.28-1.6c.223-.268.029-.702-.325-.702h-2.726l-.234-.343c-.115-.183.011-.229.228-.229h7.154l-3.885 4.754z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.z5ro-b9uf {
  stop-color: var(--svg-color--592e9c, #592e9c);
}

</style>
