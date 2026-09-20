<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGxyU4il8V)" class="r4i437pya"/><path class="pj9w_0bot"/></g><defs><linearGradient id="SVGxyU4il8V" x1="5.429" x2="17.286" y1="6.857" y2="17.714" gradientUnits="userSpaceOnUse"><stop class="dqbo-0w9t"/><stop offset="1" class="tscu1-bqh"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:eqx-background" /></template>
<style>
.dqbo-0w9t {
  stop-color: var(--svg-color--112650, #112650);
}

.ft5dv1b6b {
  fill: none;
}

.pj9w_0bot {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 20V4h16v2.286H6.286v11.428h9.143V20zm13.714-9.714H8V8h12v12h-2.286v-5.143H8v-2.286h9.714z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.tscu1-bqh {
  stop-color: var(--svg-color--38a28b, #38a28b);
}

</style>
