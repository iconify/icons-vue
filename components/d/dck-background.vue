<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGBUCtyCnE)" class="r4i437pya"/><path class="pd5uvft2f"/></g><defs><linearGradient id="SVGBUCtyCnE" x1="19.987" x2="4.002" y1="8.661" y2="8.661" gradientUnits="userSpaceOnUse"><stop class="r-xrmhbkv"/><stop offset="1" class="wn7x46btp"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dck-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.pd5uvft2f {
  fill: var(--svg-color--fff, #fff);
  d: path("m17.08 8.601l-.017.004l-7.698 7.855a1.11 1.11 0 0 1-1.588.008L4.39 13.04c-.828-.831-.248-2.24.907-2.24h1.948c.34 0 .668.133.916.373l1.8 1.731l-.92 1l-1.8-1.704H5.413l3.156 3.136l7.55-7.727a1.34 1.34 0 0 1 .96-.408h1.464c1.3 0 1.948 1.616 1.02 2.556l-6.623 6.69a1.176 1.176 0 0 1-1.688-.015l-.452-.468l.96-.964l.344.36l6.52-6.559c.071-.072.02-.2-.08-.2h-1.469z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r-xrmhbkv {
  stop-color: var(--svg-color--097cb8, #097cb8);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.wn7x46btp {
  stop-color: var(--svg-color--8adecf, #8adecf);
}

</style>
