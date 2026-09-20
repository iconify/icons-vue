<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGJrPTRcfp)" class="r4i437pya"/><path class="emj1jxabe"/></g><defs><linearGradient id="SVGJrPTRcfp" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="c499ssbjg"/><stop offset="1" class="meaoonbxx"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lbr-background" /></template>
<style>
.c499ssbjg {
  stop-color: var(--svg-color--fb9c96, #fb9c96);
}

.emj1jxabe {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.533 17.333h5.69L6.417 13.04L12 6.123l5.67 6.917l-3.937 4.293h5.734v-1.6h-2.288l2.288-2.693L12 4l-7.467 9.04l2.368 2.693H4.533zM19.467 18.4H4.533V20h14.934z");
}

.ft5dv1b6b {
  fill: none;
}

.meaoonbxx {
  stop-color: var(--svg-color--5c9ded, #5c9ded);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
