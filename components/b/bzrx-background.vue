<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG5l3Z4LtL)" class="r4i437pya"/><path class="igim3s5lu"/></g><defs><linearGradient id="SVG5l3Z4LtL" x1="18.96" x2="6.16" y1="18.96" y2="6.16" gradientUnits="userSpaceOnUse"><stop offset=".159" class="ls8pmobci"/><stop offset="1" class="n1y79_3dl"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bzrx-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.igim3s5lu {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 7.2A3.2 3.2 0 0 1 7.2 4H9v3.5h1.5V4h6.3A3.2 3.2 0 0 1 20 7.2v9.6a3.2 3.2 0 0 1-3.2 3.2H7.2A3.2 3.2 0 0 1 4 16.8v-6.3h9.101c.321 0 .399.21.399.531V13c0 .322-.179.5-.5.5h-2.019c-.321 0-.481-.252-.481-.574V11.5H9v1.656C9 14.36 9.777 15 10.981 15h2.12C14.305 15 15 14.361 15 13.156V11.03C15 9.825 14.305 9 13.1 9H4z");
}

.ls8pmobci {
  stop-color: var(--svg-color--003cda, #003cda);
}

.n1y79_3dl {
  stop-color: var(--svg-color--33dfcc, #33dfcc);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
