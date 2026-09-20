<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGdfzPfe8A)" class="r4i437pya"/><path class="j6eldtbsd"/></g><defs><linearGradient id="SVGdfzPfe8A" x1="6.349" x2="17.397" y1="6.797" y2="18.04" gradientUnits="userSpaceOnUse"><stop class="v6co0sbfj"/><stop offset="1" class="hv4sh8eqf"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:aimx-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hv4sh8eqf {
  stop-color: var(--svg-color--00a790, #00a790);
}

.j6eldtbsd {
  fill: var(--svg-color--fff, #fff);
  d: path("m10.78 4.813l-.074.057c-1.087 1.133-.406 3.667-1.001 5.663c-.56 1.887-3.438 2.963-4.656 4.118a2.854 2.854 0 1 0 3.918 4.13h.011a2.1 2.1 0 0 0 .492-.761l.029-.08v-.029q.07-.172.114-.355c.55-2.013.206-5.433.675-6.657c.59-1.539 1.653-2.317 2.54-3.169c.612-.583 1-1.201.909-1.876v-.04a1.716 1.716 0 0 0-2.122-1.487a1.74 1.74 0 0 0-.835.486m5.788 13.195a1.716 1.716 0 1 0 3.432 0a1.716 1.716 0 0 0-3.432 0");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.v6co0sbfj {
  stop-color: var(--svg-color--135554, #135554);
}

</style>
