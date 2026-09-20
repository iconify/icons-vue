<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGdKJaIVBL)" class="r4i437pya"/><path class="t4ri16bjk"/></g><defs><linearGradient id="SVGdKJaIVBL" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="ddp7g1z1f"/><stop offset="1" class="zew71i4ui"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lsd-background" /></template>
<style>
.ddp7g1z1f {
  stop-color: var(--svg-color--6f76fb, #6f76fb);
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.t4ri16bjk {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.155 20c-2.875-3.21-4.72-4.5-6.4-4.5c-1.485 0-2.85 1.03-4.685 2.5l-.87-1c2.655-4.35 1.185-6.385-1.45-9.95L5.615 6c4.235 2.65 7.29 3.93 11.6-2l1.07.74c-1.065 2.36-1.475 4.31-1.45 6.15c.035 2.7 1.08 5.16 2.415 8.325z");
}

.zew71i4ui {
  stop-color: var(--svg-color--2730ec, #2730ec);
}

</style>
