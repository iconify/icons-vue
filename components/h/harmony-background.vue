<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGz2r3bc9n)" class="r4i437pya"/><path class="gm80jrvuw"/></g><defs><linearGradient id="SVGz2r3bc9n" x1="5.013" x2="18.895" y1="18.789" y2="4.869" gradientUnits="userSpaceOnUse"><stop class="tzi0cjbjn"/><stop offset="1" class="m4k59qb9b"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:harmony-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gm80jrvuw {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.548 4.022a3.45 3.45 0 0 0-3.452 3.44v3.816c-.356.024-.72.04-1.096.04s-.739.014-1.096.036V7.463a3.452 3.452 0 0 0-6.904 0v9.118a3.452 3.452 0 0 0 6.904 0v-3.815q.533-.038 1.096-.04c.377 0 .739-.014 1.096-.036v3.891a3.452 3.452 0 0 0 6.904 0V7.463a3.45 3.45 0 0 0-3.452-3.441m-9.096 1.41a2.036 2.036 0 0 1 2.037 2.03v4.04c-1.01.147-1.996.426-2.933.83a5.3 5.3 0 0 0-1.138.68v-5.55a2.036 2.036 0 0 1 2.034-2.03m2.037 11.15a2.037 2.037 0 0 1-4.075 0v-.916c0-.808.64-1.573 1.713-2.05a10 10 0 0 1 2.362-.69zm7.06 2.03a2.036 2.036 0 0 1-2.038-2.03v-4.04a11.6 11.6 0 0 0 2.933-.83a5.3 5.3 0 0 0 1.138-.68v5.55a2.036 2.036 0 0 1-2.034 2.03m.324-8.19c-.756.326-1.55.558-2.362.69v-3.65a2.038 2.038 0 0 1 4.075 0v.915c0 .805-.64 1.57-1.713 2.045");
}

.m4k59qb9b {
  stop-color: var(--svg-color--69fabd, #69fabd);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.tzi0cjbjn {
  stop-color: var(--svg-color--00aee9, #00aee9);
}

</style>
