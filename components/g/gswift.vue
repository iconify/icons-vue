<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGtaW3geJD)" class="ffrwvug3j"/><path class="o7wauhbgj"/><path class="vcp20lofe"/><defs><linearGradient id="SVGtaW3geJD" x1="16.24" x2="6.136" y1="7.947" y2="17.665" gradientUnits="userSpaceOnUse"><stop class="lzf_okbgo"/><stop offset="1" class="i5xo1203r"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gswift" /></template>
<style>
.ffrwvug3j {
  d: path("M3 16.948L8.625 10.9l1.125.55l-1.688 1.925l3.097-1.377l1.403.824z");
}

.ft5dv1b6b {
  fill: none;
}

.i5xo1203r {
  stop-color: var(--svg-color--fff000, #fff000);
}

.lzf_okbgo {
  stop-color: var(--svg-color--ffa902, #ffa902);
}

.o7wauhbgj {
  fill: var(--svg-color--fff, #fff);
  d: path("m21 16.95l-5.063-5.225L18.75 10.2l-3.375-3.15h-6.75L5.25 10.2zm-11.813-9h5.625l1.972 1.85l-1.972.823L13.8 9.75H9.75l2.475.9h1.125l2.587 2.727l-8.72-3.578z");
}

.vcp20lofe {
  fill: var(--svg-color--e9e9e9, #e9e9e9);
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("m16.361 11.517l-1.026-1.111l-.522.216l-.315-.302l1.44 1.404z");
}

</style>
