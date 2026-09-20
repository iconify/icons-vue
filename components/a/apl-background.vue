<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG6ZWXHXIt)" class="r4i437pya"/><path class="qwv3uabfi"/></g><defs><linearGradient id="SVG6ZWXHXIt" x1="7.048" x2="18.343" y1="4.857" y2="21.033" gradientUnits="userSpaceOnUse"><stop class="qepogybki"/><stop offset="1" class="u28bw3nsy"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:apl-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qepogybki {
  stop-color: var(--svg-color--5e9ff9, #5e9ff9);
}

.qwv3uabfi {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.347 4.015c-.138.014-.205.049-.237.118c-.047.101-.008.186.796 1.813c.211.423.395.817.41.874a.8.8 0 0 1-.003.414c-.014.06-.184.429-.377.821c-.484.984-.715 1.46-2.66 5.476L4.95 18.334c-.385.792-.63 1.317-.643 1.377c-.026.121 0 .187.095.242c.062.036.094.038 1.086.043c1.203.006 1.424-.005 1.582-.08c.215-.099.259-.164.604-.874c.17-.352.533-1.095.805-1.652s.966-1.991 1.544-3.184c1.189-2.455 1.893-3.898 1.915-3.92c.055-.056.537.923 4.124 8.358c.271.564.525 1.066.561 1.115a.7.7 0 0 0 .138.138c.147.103.148.103 1.375.103c1.006 0 1.154-.004 1.346-.035a3 3 0 0 0 .223-.04a3 3 0 0 0-.1-.274c-.115-.29-.209-.483-2.952-6.13Q14.76 9.637 12.88 5.746c-.717-1.487-.7-1.454-.832-1.576c-.19-.175-.148-.17-1.456-.17c-.615 0-1.176.007-1.244.015");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.u28bw3nsy {
  stop-color: var(--svg-color--0050f9, #0050f9);
}

</style>
