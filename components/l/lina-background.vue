<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGN50prdSY)" class="r4i437pya"/><path class="il0up2b2y"/></g><defs><linearGradient id="SVGN50prdSY" x1="10.627" x2="21.351" y1="10.693" y2="21.946" gradientUnits="userSpaceOnUse"><stop class="ajj2gmhpi"/><stop offset="1" class="dxhpq-qwg"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lina-background" /></template>
<style>
.ajj2gmhpi {
  stop-color: var(--svg-color--6bb7ff, #6bb7ff);
}

.dxhpq-qwg {
  stop-color: var(--svg-color--053bf7, #053bf7);
}

.ft5dv1b6b {
  fill: none;
}

.il0up2b2y {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.458 14.264a1.975 1.975 0 0 1 0-2.772L12.869 4l.346.35a1.975 1.975 0 0 1 0 2.77l-7.412 7.493zm2.664 2.693a1.974 1.974 0 0 1 0-2.772l7.411-7.492l.346.35a1.974 1.974 0 0 1 0 2.771l-7.412 7.492zm2.664-.077a1.975 1.975 0 0 0 0 2.77l.345.35l7.412-7.492a1.975 1.975 0 0 0 0-2.771l-.345-.35z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
