<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGX5Lutbbi)" class="r4i437pya"/><path class="yisds-7sy"/></g><defs><linearGradient id="SVGX5Lutbbi" x1="7.461" x2="17.365" y1="15.572" y2="5.051" gradientUnits="userSpaceOnUse"><stop class="ea17l_-qp"/><stop offset="1" class="edza-vyle"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:alot-background" /></template>
<style>
.ea17l_-qp {
  stop-color: var(--svg-color--eb1357, #eb1357);
}

.edza-vyle {
  stop-color: var(--svg-color--db23c8, #db23c8);
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

.yisds-7sy {
  fill: var(--svg-color--fff, #fff);
  d: path("m20 10.036l-3.617 2.373c2.852-2.31 2.852-4.812 2.852-4.812l-3.78 3.794C18 7.104 17.066 5.335 17.066 5.335l-3.012 5.168a7.5 7.5 0 0 0-2.026-.276h-.049c-.684 0-1.364.089-2.026.276L6.937 5.335s-1.057 1.622 1.489 5.91L4.773 7.6S4.4 9.813 7.448 12.27C7.43 12.298 4 10.036 4 10.036s-.089 2.133 2.933 3.839v.058c0 2.31 2.252 4.71 5.047 4.732h.044c2.79-.027 5.048-2.417 5.048-4.732v-.058C20.089 12.169 20 10.036 20 10.036m-9.704 6.22s-.893.063-1.408-.48c-.516-.537-.454-1.474-.454-1.474s.898-.063 1.413.48c.516.541.45 1.479.45 1.479zm4.825-.48c-.515.543-1.408.485-1.408.485s-.058-.938.457-1.48c.516-.542 1.409-.48 1.409-.48s.053.934-.467 1.476z");
}

</style>
