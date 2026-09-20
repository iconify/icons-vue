<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGfkRApe3C)" class="r4i437pya"/><path class="j6gflpbnv"/></g><defs><linearGradient id="SVGfkRApe3C" x1="5.479" x2="15.314" y1="17.698" y2="9.22" gradientUnits="userSpaceOnUse"><stop class="nb9a_lbxh"/><stop offset="1" class="fdrp62-hm"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gas-background" /></template>
<style>
.fdrp62-hm {
  stop-color: var(--svg-color--52ba00, #52ba00);
}

.ft5dv1b6b {
  fill: none;
}

.j6gflpbnv {
  fill: var(--svg-color--fff, #fff);
  d: path("m18.824 17.264l-5.648-2.608V8.88l5.647-1.984zm-8 2.736l-5.647-2.544V7.168l5.647 2.544zm0-10.688L5.392 6.808L13.333 4l5.402 2.512z");
}

.nb9a_lbxh {
  stop-color: var(--svg-color--beea2e, #beea2e);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
