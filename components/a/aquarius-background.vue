<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ui2_sjbrc"/><path clip-rule="evenodd" class="ngzif1ynv"/><path clip-rule="evenodd" class="m1fqhjdws"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:aquarius-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m1fqhjdws {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("m13.832 6.562l2.54 2.53l2.521-2.514L20 7.676l-3.628 3.616l-2.54-2.53l-4.004 3.99l-2.15-2.141l-2.572 2.563L4 12.076L7.679 8.41l2.149 2.14Z");
}

.ngzif1ynv {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("m13.832 10.828l2.54 2.53l2.521-2.514L20 11.94l-3.628 3.616l-2.54-2.53l-4.004 3.99l-2.15-2.14l-2.572 2.562L4 16.34l3.679-3.665l2.149 2.14Z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.ui2_sjbrc {
  fill: var(--svg-color--872ab0, #872ab0);
  d: path("M24 0H0v24h24z");
}

</style>
