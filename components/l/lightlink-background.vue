<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGyXZNZIIB)" class="r4i437pya"/><path class="h5raevnys"/><path class="y7282-b-h"/></g><defs><linearGradient id="SVGyXZNZIIB" x1="9.132" x2="13.232" y1="10.936" y2="15.257" gradientUnits="userSpaceOnUse"><stop offset=".117" class="oxg89m8kg"/><stop offset=".188" class="n3i64cbbo"/><stop offset=".348" class="r6bsw0b0n"/><stop offset=".507" class="xb7n26a9b"/><stop offset=".662" class="ll1o_6blo"/><stop offset=".808" class="ef85f7rmq"/><stop offset="1" class="ddkoktb1k"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lightlink-background" /></template>
<style>
.ddkoktb1k {
  stop-color: var(--svg-color--67fffc, #67fffc);
}

.ef85f7rmq {
  stop-color: var(--svg-color--36cbff, #36cbff);
}

.ft5dv1b6b {
  fill: none;
}

.h5raevnys {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.26 10.82a.54.54 0 0 1 0 .79a.63.63 0 0 1-.844 0l-1.264-1.186l-2.78 2.611a.63.63 0 0 1-.843 0a.533.533 0 0 1 0-.79l3.162-2.964l.04-.042a.623.623 0 0 1 .843 0z");
}

.ll1o_6blo {
  stop-color: var(--svg-color--39c7ff, #39c7ff);
}

.n3i64cbbo {
  stop-color: var(--svg-color--6087ff, #6087ff);
}

.oxg89m8kg {
  stop-color: var(--svg-color--6978ff, #6978ff);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.r6bsw0b0n {
  stop-color: var(--svg-color--4da5ff, #4da5ff);
}

.xb7n26a9b {
  stop-color: var(--svg-color--40baff, #40baff);
}

.y7282-b-h {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.447 10.97a.533.533 0 0 1 0 .79l-3.162 2.959l-.04.042a.623.623 0 0 1-.843 0l-1.685-1.58a.54.54 0 0 1 0-.79a.63.63 0 0 1 .842 0l1.265 1.185l2.78-2.607a.63.63 0 0 1 .843 0m3.381.013a.63.63 0 0 0-.843 0l-1.68 1.58a.533.533 0 0 0 0 .79a.63.63 0 0 0 .842 0l1.685-1.58a.544.544 0 0 0-.004-.79M5.015 13.026a.63.63 0 0 1-.843 0a.54.54 0 0 1 0-.79l1.685-1.58a.63.63 0 0 1 .843 0a.533.533 0 0 1 0 .79z");
}

</style>
