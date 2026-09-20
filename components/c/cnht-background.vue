<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="h6fbybcgs"/><path class="s76umdmpn"/><path clip-rule="evenodd" class="a--5fob-e"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cnht-background" /></template>
<style>
.a--5fob-e {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M6.972 4.8h10.034L20 11.322L12 19.2l-8-7.878zm4.228 7.583V16h1.6v-3.617c2.27-.095 4.001-.588 4.001-1.183s-1.73-1.088-4.001-1.184V8.8h2.8V7.2H8.4v1.6h2.8v1.217c-2.27.095-3.998.588-3.998 1.183c0 .594 1.729 1.088 3.998 1.183");
}

.ft5dv1b6b {
  fill: none;
}

.h6fbybcgs {
  fill: var(--svg-color--009f74, #009f74);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.s76umdmpn {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.2 10.413c-2.048.068-3.6.394-3.6.786c0 .442 1.97.8 4.4.8s4.4-.358 4.4-.8c0-.392-1.552-.718-3.6-.786v1.186h-1.6z");
}

</style>
