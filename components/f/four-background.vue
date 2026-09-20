<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG7WChod5z)" class="r4i437pya"/><path class="r5vdex9ej"/><path clip-rule="evenodd" class="yswnjybds"/></g><defs><linearGradient id="SVG7WChod5z" x1="19.45" x2="7.253" y1="4.469" y2="21.68" gradientUnits="userSpaceOnUse"><stop class="u1swwbwez"/><stop offset="1" class="iixe92buh"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:four-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.iixe92buh {
  stop-color: var(--svg-color--3c554f, #3c554f);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.r5vdex9ej {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.866 12L12 11.467V8.8l-.534.267l-1.6 2.4z");
}

.u1swwbwez {
  stop-color: var(--svg-color--92988a, #92988a);
}

.yswnjybds {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M4 6.352L20 4v14.587L4 20zm9.6 4.849v-4h-2.133L7.733 12v1.6L12 13.066V16.8l1.6-.534V12.8l2.133-.534v-1.6z");
}

</style>
