<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGfh5PGc3i)" class="r4i437pya"/><path class="d5hmigbko"/></g><defs><linearGradient id="SVGfh5PGc3i" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="kgvvfobkb"/><stop offset=".83" class="q0ld9ljem"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dextf-background" /></template>
<style>
.d5hmigbko {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 18.112V5.888C4 4.843 4.853 4 5.92 4h5.957C16.357 4 20 7.584 20 12s-3.637 8-8.123 8H5.915A1.897 1.897 0 0 1 4 18.112m1.355-4.944l2.602.565L13.6 9.11v7.28l2.133 1.824V6.987L14.3 6.203l-8.944 6.96z");
}

.ft5dv1b6b {
  fill: none;
}

.kgvvfobkb {
  stop-color: var(--svg-color--72f64b, #72f64b);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q0ld9ljem {
  stop-color: var(--svg-color--2d6a1c, #2d6a1c);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
