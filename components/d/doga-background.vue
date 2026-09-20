<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGsEZUGcox)" class="r4i437pya"/><path clip-rule="evenodd" class="fj4gj-ble"/><path class="b0h04qqvo"/><path clip-rule="evenodd" class="m7zb1db8u"/><path class="czvwuq5jy"/></g><defs><linearGradient id="SVGsEZUGcox" x1="6.429" x2="17.285" y1="6.858" y2="17" gradientUnits="userSpaceOnUse"><stop class="phbljubkl"/><stop offset="1" class="qs1d5vblb"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:doga-background" /></template>
<style>
.b0h04qqvo {
  fill: var(--svg-color--fff, #fff);
  d: path("m16.403 15.547l-2.075.59a5 5 0 0 1-.303.425l1.086 1.274a6.3 6.3 0 0 0 1.291-2.29");
}

.czvwuq5jy {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.966 10.62L7.31 8.967h1.656z");
}

.fj4gj-ble {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M10.345 7.31H4V20h6.345a6.346 6.346 0 0 0 4.486-10.83a6.35 6.35 0 0 0-4.486-1.86m0 1.656h-4.69v9.379h4.69a4.69 4.69 0 0 0 0-9.38");
}

.ft5dv1b6b {
  fill: none;
}

.m7zb1db8u {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M13.655 4H7.31v12.69h6.345a6.345 6.345 0 1 0 0-12.69m0 1.655h-4.69v9.38h4.69a4.69 4.69 0 1 0 0-9.38");
}

.phbljubkl {
  stop-color: var(--svg-color--422c81, #422c81);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qs1d5vblb {
  stop-color: var(--svg-color--7b368a, #7b368a);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
