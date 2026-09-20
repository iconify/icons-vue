<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGlICFOcjs)" class="r4i437pya"/><path clip-rule="evenodd" class="d9lbjk8_u"/><path class="iy444_b0m"/></g><defs><linearGradient id="SVGlICFOcjs" x1="4.89" x2="19.11" y1="12" y2="12" gradientUnits="userSpaceOnUse"><stop class="em-tch5kn"/><stop offset="1" class="nymso310x"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:abt-background" /></template>
<style>
.d9lbjk8_u {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("m12 4l7.11 4v8L12 20l-7.11-4V8zm6.444 4.125l-6.222-3.5v7zm.222.375L12.444 12l6.222 3.5zm-.222 7.375l-6.222-3.5v7zm-6.666 3.5l-6.222-3.5l6.222-3.5zm0-7.75l-6.222-3.5l6.222-3.5zM5.334 8.5l6.222 3.5l-6.222 3.5z");
}

.em-tch5kn {
  stop-color: var(--svg-color--06efa0, #06efa0);
}

.ft5dv1b6b {
  fill: none;
}

.iy444_b0m {
  fill: var(--svg-color--000, #000);
  d: path("m12.002 7.69l3.747 6.325l-3.748 2.109l-3.747-2.108zm0 .867l-3.141 5.3l3.14 1.767l3.141-1.767z");
}

.nymso310x {
  stop-color: var(--svg-color--01fafc, #01fafc);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
