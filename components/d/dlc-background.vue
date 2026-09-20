<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGMnBjYcHZ)" class="r4i437pya"/><path clip-rule="evenodd" class="w42ktdy6m"/></g><defs><linearGradient id="SVGMnBjYcHZ" x1="4.536" x2="19.464" y1="12" y2="12" gradientUnits="userSpaceOnUse"><stop class="t25sync1b"/><stop offset="1" class="t3ietpblc"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dlc-background" /></template>
<style>
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

.t25sync1b {
  stop-color: var(--svg-color--16e0b0, #16e0b0);
}

.t3ietpblc {
  stop-color: var(--svg-color--14c5d7, #14c5d7);
}

.w42ktdy6m {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M4.536 4.501v4.852l1.562 1.92l-1.562 2.388v5.838A.5.5 0 0 0 5.03 20h7.129c.384-.005 7.304-.405 7.304-7.79c0-5.896-4.564-8.21-7.31-8.21H5.037a.5.5 0 0 0-.501.501m1.066 4.132L6.77 10.26l1.013-1.802a.34.34 0 0 1 .303-.192h6.766c.123 0 .235.07.293.17l1.67 2.683a.34.34 0 0 1-.027.373L12 17.649a.53.53 0 0 1-.395.218a.52.52 0 0 1-.405-.213l-4.425-5.46l-1.173 1.83v4.568c0 .187.15.336.336.336h6.2c2.085-.074 6.26-1.562 6.26-6.904c0-5.337-4.175-6.862-6.26-6.958h-6.2a.336.336 0 0 0-.336.336zm5.214.699L9.782 10.93H7.569l.907-1.6zm-2.932 2.132l2.666 3.626l-.81-3.626zm6.504-2.132h-2.335l1.034 1.599h2.208zm.597 2.132l-2.665 3.711l.805-3.71h1.866zm-4.542-.533h1.962l-.97-1.6zm2.1.533h-2.239l1.13 4.532z");
}

</style>
