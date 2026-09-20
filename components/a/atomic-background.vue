<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="q0xxguned"/><path fill="url(#SVGpdFNN8JH)" clip-rule="evenodd" class="clf1x_bej"/></g><defs><linearGradient id="SVGpdFNN8JH" x1="4" x2="4" y1="4.5" y2="19.5" gradientUnits="userSpaceOnUse"><stop class="fswko_bmi"/><stop offset="1" class="c-2x1jbnv"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:atomic-background" /></template>
<style>
.c-2x1jbnv {
  stop-color: var(--svg-color--1f8efa, #1f8efa);
}

.clf1x_bej {
  fill-rule: evenodd;
  d: path("M4 19.5L8.748 6.84c.602-1.479 1.726-2.315 3.219-2.34h.066c1.494.025 2.617.861 3.22 2.34L20 19.5l-2.94-.995L13.004 7.69c-.247-.599-.532-.814-1.005-.823c-.472.01-.756.225-1.003.823L6.94 18.505zm10.066-4.821c0 1.106-.913 2.002-2.038 2.002c-1.126 0-2.038-.896-2.038-2.002s.912-2.002 2.038-2.002s2.038.896 2.038 2.002");
}

.fswko_bmi {
  stop-color: var(--svg-color--42c1fd, #42c1fd);
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q0xxguned {
  fill: var(--svg-color--212e4f, #212e4f);
  d: path("M24 0H0v24h24z");
}

</style>
