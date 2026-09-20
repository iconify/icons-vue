<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGct2oCCkI)" class="r4i437pya"/><path class="fjhk6tbai"/></g><defs><linearGradient id="SVGct2oCCkI" x1="6.84" x2="17.322" y1="17.4" y2="8.254" gradientUnits="userSpaceOnUse"><stop class="ahz_z2bxj"/><stop offset="1" class="vkycpjbso"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gmee-background" /></template>
<style>
.ahz_z2bxj {
  stop-color: var(--svg-color--5945fc, #5945fc);
}

.fjhk6tbai {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.889 4h2.667v1.009c2.897.471 4.23 2.324 4.693 4.769h-3.271C14.538 8.693 13.644 8 12 8c-2.191 0-3.333 1.733-3.333 4.004c0 2.276 1.217 3.894 3.333 3.992c1.875.088 2.778-.845 3.138-2.218h-2.472v-2.222h5.77l.008.55c0 3.539-1.11 6.476-4.888 6.943V20h-2.667v-1.018c-3.405-.6-5.334-3.266-5.334-6.875c0-3.623 1.823-6.623 5.334-7.138z");
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

.vkycpjbso {
  stop-color: var(--svg-color--3d9eef, #3d9eef);
}

</style>
