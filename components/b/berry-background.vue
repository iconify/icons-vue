<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG4ItMbcBC)" class="r4i437pya"/><path class="csf2g0emj"/></g><defs><linearGradient id="SVG4ItMbcBC" x1="8.965" x2="14.567" y1="4.562" y2="20" gradientUnits="userSpaceOnUse"><stop class="ks0j3nb5q"/><stop offset="1" class="p_pjt-b9a"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:berry-background" /></template>
<style>
.csf2g0emj {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.935 19.997c-2.256-.114-4.034-1.872-4.034-3.985c0-.138.089-.277.208-.36c.772-.443 1.277-1.218 1.277-2.132c0-1.385-1.188-2.52-2.673-2.52h-2.584C9.505 11 9 11.47 9 12.08V20H6.176A2.177 2.177 0 0 1 4 17.826v-7.764c0-.734.367-1.411.961-1.806l5.824-3.896a2.23 2.23 0 0 1 2.431 0l5.824 3.896a2.17 2.17 0 0 1 .96 1.806v7.735a2.183 2.183 0 0 1-2.065 2.2");
}

.ft5dv1b6b {
  fill: none;
}

.ks0j3nb5q {
  stop-color: var(--svg-color--28d0fa, #28d0fa);
}

.p_pjt-b9a {
  stop-color: var(--svg-color--635bd7, #635bd7);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
