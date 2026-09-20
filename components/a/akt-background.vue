<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="zlmf_4bsz"/><path class="heh1scb-o"/><path class="tg6x7a8of"/><path class="d4_9rwbnv"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:akt-background" /></template>
<style>
.d4_9rwbnv {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.8 9.556L4 14.223l2.8 4.666l5.644-9.333z");
}

.ft5dv1b6b {
  fill: none;
}

.heh1scb-o {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.334 14.444L12 18.888h5.333l-2.666-4.445z");
  opacity: var(--svg-opacity--0-6, 0.6);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.tg6x7a8of {
  fill: var(--svg-color--fff, #fff);
  d: path("m8.89 5.11l8.457 13.778L20 14.279l-5.804-9.168z");
}

.zlmf_4bsz {
  fill: var(--svg-color--db4533, #db4533);
  d: path("M24 0H0v24h24z");
}

</style>
