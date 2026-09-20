<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="lo2nedc8h"/><path fill="url(#SVGx8Ej4bQH)" class="ykz6em0wk"/><path fill="url(#SVG3cgboeHH)" class="fiunfibuy"/><path class="gw2-335tu"/><path fill="url(#SVGvguJHeLS)" class="i5ec8wqzi"/></g><defs><linearGradient id="SVGx8Ej4bQH" x1="12" x2="12" y1="6.222" y2="17.777" gradientUnits="userSpaceOnUse"><stop class="ya1cer-kb"/><stop offset=".36" class="g97rqb4yo"/><stop offset=".65" class="tr4f5vbks"/><stop offset="1" class="r5d2ox8us"/></linearGradient><linearGradient id="SVG3cgboeHH" x1="12" x2="12" y1="6.223" y2="17.778" gradientUnits="userSpaceOnUse"><stop offset=".06" class="s796_bcvb"/><stop offset=".39" class="hqpb802-y"/><stop offset="1" class="jpsysbbun"/></linearGradient><linearGradient id="SVGvguJHeLS" x1="12" x2="12" y1="6.222" y2="12.177" gradientUnits="userSpaceOnUse"><stop class="l366kmcri"/><stop offset=".38" class="qt8tvuowz"/><stop offset=".93" class="aqwnttmfq"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gg-background" /></template>
<style>
.aqwnttmfq {
  stop-color: var(--svg-color--fca143, #fca143);
}

.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.fiunfibuy {
  d: path("m12 14.72l-5.333 3.058v-5.6L12 9.174z");
}

.ft5dv1b6b {
  fill: none;
}

.g97rqb4yo {
  stop-color: var(--svg-color--e26891, #e26891);
}

.gw2-335tu {
  fill: var(--svg-color--5e2693, #5e2693);
  d: path("m12 14.72l5.333 3.058v-5.6L12 9.174z");
}

.hqpb802-y {
  stop-color: var(--svg-color--ea6d75, #ea6d75);
}

.i5ec8wqzi {
  d: path("M6.667 12.177L4 10.747l7.982-4.525L20 10.746l-2.667 1.431L11.995 9.2z");
}

.jpsysbbun {
  stop-color: var(--svg-color--b961dc, #b961dc);
}

.l366kmcri {
  stop-color: var(--svg-color--eec985, #eec985);
}

.lo2nedc8h {
  fill: var(--svg-color--5f2596, #5f2596);
  d: path("M4 16.333v-5.578l2.667 1.387v5.622z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qt8tvuowz {
  stop-color: var(--svg-color--fdbd4d, #fdbd4d);
}

.r5d2ox8us {
  stop-color: var(--svg-color--b071d9, #b071d9);
}

.s796_bcvb {
  stop-color: var(--svg-color--ef7c3b, #ef7c3b);
}

.tr4f5vbks {
  stop-color: var(--svg-color--d45ac7, #d45ac7);
}

.ya1cer-kb {
  stop-color: var(--svg-color--f17750, #f17750);
}

.ykz6em0wk {
  d: path("M20 16.333v-5.578l-2.667 1.387v5.622z");
}

</style>
