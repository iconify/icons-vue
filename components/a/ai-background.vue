<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="oz6ukn40e"/><path class="tqs-f0bni"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ai-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.oz6ukn40e {
  fill: var(--svg-color--020305, #020305);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.tqs-f0bni {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.65 11.2h-.317l.867 1.6h.266l.867-1.6h-.317l-.683 1.26zm-5.483 0h.25v1.08c0 .112.113.22.203.22h.927c.09 0 .203-.108.203-.22V11.2H8v1.2a.44.44 0 0 1-.098.283a.3.3 0 0 1-.235.117H6.5a.3.3 0 0 1-.236-.117a.44.44 0 0 1-.097-.283zm4.616 0v.3h-.533v1.3H10v-1.3h-.55v-.3zm-2.616 0h.25v1.3H9.5v.3H8.167zm9 0a.3.3 0 0 0-.236.117a.44.44 0 0 0-.098.283v.16c0 .106.035.208.098.283a.3.3 0 0 0 .236.117h.966a.1.1 0 0 1 .05.018q.024.015.04.04a.18.18 0 0 1 .03.118a.2.2 0 0 1-.015.06a.2.2 0 0 1-.033.048a.1.1 0 0 1-.046.03q-.026.009-.052.006h-1.21v.32h1.27a.3.3 0 0 0 .235-.117a.44.44 0 0 0 .098-.283v-.16a.44.44 0 0 0-.098-.283a.3.3 0 0 0-.235-.117h-.96a.13.13 0 0 1-.092-.055a.18.18 0 0 1-.032-.117a.17.17 0 0 1 .046-.11a.12.12 0 0 1 .098-.038h1.21v-.32zm-5.917 0H11v1.6h.25zm3.583 0v.3H13.75v.352h1.083v.3H13.75v.348h1.083v.3H13.5v-1.6zm5.167.3v-.3h-1.333v1.6H20v-.3h-1.083v-.352H20v-.3h-1.083V11.5zm-4.917-.3v1.6h.25v-.604h.67l.234.604h.28l-.234-.608a.32.32 0 0 0 .215-.13a.45.45 0 0 0 .085-.27V11.6a.44.44 0 0 0-.097-.283a.3.3 0 0 0-.236-.117zm.25.672v-.4h.877c.044 0 .087.021.118.059a.22.22 0 0 1 .049.141a.22.22 0 0 1-.05.141a.15.15 0 0 1-.117.059zM6 11.2h-.253l-.734 1.184l-.76-1.176V11.2H4v1.6h.25v-1.104l.71 1.104h.107l.68-1.08v1.08H6z");
}

</style>
