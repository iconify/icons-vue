<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGJfavhd8R)" class="r4i437pya"/><path class="nlyrhoqaa"/></g><defs><linearGradient id="SVGJfavhd8R" x1="7" x2="16.343" y1="5.839" y2="18.612" gradientUnits="userSpaceOnUse"><stop class="z86b6gbvz"/><stop offset=".49" class="darxqh9zt"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lif3-background" /></template>
<style>
.darxqh9zt {
  stop-color: var(--svg-color--294874, #294874);
}

.ft5dv1b6b {
  fill: none;
}

.nlyrhoqaa {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.58 5.465A1.51 1.51 0 0 1 12 4.5c.63 0 1.2.385 1.42.965L18.2 17.5H20v2h-3.5L12 7.5l-4.5 12H4v-2h1.8z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.z86b6gbvz {
  stop-color: var(--svg-color--749fc1, #749fc1);
}

</style>
