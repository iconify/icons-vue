<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGucBFvnQT)" class="r4i437pya"/><path class="u22skzbol"/><path class="k3xrh3b0f"/></g><defs><linearGradient id="SVGucBFvnQT" x1="4.25" x2="19.75" y1="12" y2="12" gradientUnits="userSpaceOnUse"><stop offset=".01" class="ab4w_fuel"/><stop offset="1" class="eoglvgb5t"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cast-background" /></template>
<style>
.ab4w_fuel {
  stop-color: var(--svg-color--cbbba0, #cbbba0);
}

.eoglvgb5t {
  stop-color: var(--svg-color--7a6037, #7a6037);
}

.ft5dv1b6b {
  fill: none;
}

.k3xrh3b0f {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.65 7.06A8.27 8.27 0 0 0 12.31 4a8.035 8.035 0 0 0-8.06 8c0 4.42 3.615 8 8.06 8c2.495 0 4.74-1.175 6.34-3.06l-1.855-1.84A5.495 5.495 0 0 1 6.75 12a5.5 5.5 0 0 1 10.045-3.1z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.u22skzbol {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.75 12a3 3 0 1 0 6.001 0a3 3 0 0 0-6.001 0");
}

</style>
