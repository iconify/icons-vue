<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG4uu1CdHe)" class="r4i437pya"/><path class="dnxczcbgq"/><path class="h3jvxu9xj"/></g><defs><linearGradient id="SVG4uu1CdHe" x1="20" x2="4" y1="12" y2="12" gradientUnits="userSpaceOnUse"><stop class="h75m_nbht"/><stop offset=".99" class="rsv_mlmew"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:fls-background" /></template>
<style>
.dnxczcbgq {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.979 15.5c2.94.744 3.574 2.169 3.52 2.788l-3.52 1.71h-.7a2.264 2.264 0 0 1-2.274-2.25c0-1.244 1.02-2.249 2.274-2.249zm2.77.164l-5.694-2.81c-.4-2.369 1.484-2.888 2.844-2.848c.355.005.7.124 1.015.284c1.414.72 3.899 1.975 5.388 2.71c1.68.825 1.8 2.12 1.65 2.664l-3.74 1.835a3.3 3.3 0 0 0-1.464-1.835");
}

.ft5dv1b6b {
  fill: none;
}

.h3jvxu9xj {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.426 12.425L4.004 7.25c0-2.6 1.92-3.25 2.954-3.25c.83 0 1.445.206 1.65.31c2.384 1.16 7.498 3.65 8.863 4.33c1.704.85 2.529 1.385 2.529 2.8c0 1.3-.55 1.965-1.065 2.23c-.795.404-2.114 1.06-2.774 1.33a3.27 3.27 0 0 0-1.735-2.575");
}

.h75m_nbht {
  stop-color: var(--svg-color--5b8aff, #5b8aff);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.rsv_mlmew {
  stop-color: var(--svg-color--3f58ff, #3f58ff);
}

</style>
