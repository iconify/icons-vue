<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGKULYMcfB)" class="r4i437pya"/><path class="gdywegcjt"/><path class="k8cx90sak"/></g><defs><linearGradient id="SVGKULYMcfB" x1="17.35" x2="15.291" y1="8.693" y2="16.827" gradientUnits="userSpaceOnUse"><stop class="ge0suc4ov"/><stop offset=".8" class="rrlothbbr"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:hook-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gdywegcjt {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.984 8c1.916 0 3.12 1.24 3.48 1.856l-2.856.616l.792-.616c-1.812-1.292-4.2.34-4.2 2.04c0 1.364 1.136 2.248 1.648 2.52c-1.544-.216-2.568-1.264-2.672-1.6a3.2 3.2 0 0 1-.176-.92C4 9.984 5.588 8 7.984 8m8.032 8c-1.916 0-3.12-1.24-3.48-1.856l2.856-.616l-.792.616c1.812 1.292 4.2-.34 4.2-2.04c0-1.364-1.137-2.248-1.649-2.52c1.544.216 2.568 1.264 2.672 1.6c.084.272.176.604.176.92C20 14.02 18.411 16 16.016 16");
}

.ge0suc4ov {
  stop-color: var(--svg-color--68d869, #68d869);
}

.k8cx90sak {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.028 14.572a3.48 3.48 0 0 1-2.88-1.44c.22 1.36 1.8 2.868 3.884 2.868c1.672 0 3.128-1.46 3.648-2.192l2.056-3.036c.384-.468 1.484-1.404 2.784-1.404s2.86.936 3.48 1.404c-.264-.916-1.332-2.744-3.48-2.744s-3.612 1.52-4.08 2.28c-.78 1.056-2.412 3.244-2.708 3.5c-.368.32-.72.764-2.704.764");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.rrlothbbr {
  stop-color: var(--svg-color--c6f88a, #c6f88a);
}

</style>
