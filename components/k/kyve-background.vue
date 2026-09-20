<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGdRs0weru)" class="r4i437pya"/><path class="i_4fz_buy"/></g><defs><linearGradient id="SVGdRs0weru" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="kw2himb5s"/><stop offset="1" class="r0x0v5s4j"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kyve-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i_4fz_buy {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.857 20L8.24 4h3.063l-1.406 6.623h.554L15.548 4h3.595v.309l-6.126 7.542v.355l3.926 7.565V20h-3.417l-3.343-6.623h-.875L7.897 20z");
}

.kw2himb5s {
  stop-color: var(--svg-color--151e1d, #151e1d);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r0x0v5s4j {
  stop-color: var(--svg-color--23584e, #23584e);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
