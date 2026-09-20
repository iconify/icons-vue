<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="rwjqxmbst"/><path class="q7eli3b7h"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:equad-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q7eli3b7h {
  fill: var(--svg-color--fff, #fff);
  d: path("m16.046 18.898l.96 1.095h2.5l-5.5-6h-2.25l2.945 3.365a6 6 0 1 1 1.775-1.355l1.33 1.5a8 8 0 1 0-1.755 1.395z");
}

.rwjqxmbst {
  fill: var(--svg-color--191a4c, #191a4c);
  d: path("M24 0H0v24h24z");
}

</style>
