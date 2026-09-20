<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGkSSpoe0E)" class="r4i437pya"/><path class="cyshs1bad"/><path class="od0p0_b4c"/><path class="al098vsas"/></g><defs><linearGradient id="SVGkSSpoe0E" x1="5.552" x2="9.911" y1="8.792" y2="19.451" gradientUnits="userSpaceOnUse"><stop class="vwmmxyb8o"/><stop offset="1" class="y8_40qrsu"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:land-background" /></template>
<style>
.al098vsas {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.003 18.022L12.004 20l6.915-4.108V8.108L12 12l.002 3.89l5.187-3.025v2.162z");
}

.cyshs1bad {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.812 9.082v5.923L12 18.023V20l-6.919-4.108V8.108z");
}

.ft5dv1b6b {
  fill: none;
}

.od0p0_b4c {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.54 10.055v3.89L12 15.892v-3.89zm0-3.989L12.044 4l6.875 4.108L12 12l-3.46-1.946zM6.812 7.087l-1.73 1.02l1.73.974z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.vwmmxyb8o {
  stop-color: var(--svg-color--5c93f7, #5c93f7);
}

.y8_40qrsu {
  stop-color: var(--svg-color--1159df, #1159df);
}

</style>
