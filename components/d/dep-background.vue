<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="kt7aq8m2c"/><path class="am11bkb0s"/><path clip-rule="evenodd" class="nko62hatv"/><path class="dlvmrnbqh"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dep-background" /></template>
<style>
.am11bkb0s {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.899 5.49L7.818 9.91h8.344l-1.114-4.42zM20 13.474l-3.498-3.09l-4.173 6.833l4.596 1.293z");
}

.dlvmrnbqh {
  fill: var(--svg-color--fff, #fff);
  d: path("m4 13.475l3.5-3.09l4.172 6.832l-4.597 1.294z");
}

.ft5dv1b6b {
  fill: none;
}

.kt7aq8m2c {
  fill: var(--svg-color--eab74c, #eab74c);
  d: path("M24 0H0v24h24z");
}

.nko62hatv {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M15.438 10.305h.556l-3.961 6.38l-4.006-6.38h5.928L12.72 12.61l.622.993zm-6.596.402h2.108l2.13 3.33l-1.047 1.737zm4.452 0h-1.809l.985 1.478z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
