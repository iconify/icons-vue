<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="il-_7smwy"/><path class="mxawm9bvf"/><path class="bsni2_t1b"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dor-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.bsni2_t1b {
  fill: var(--svg-color--1c4387, #1c4387);
  d: path("m9.9 11.972l2.1 2.133l2.108-2.14l.707.701L12 15.546l-2.824-2.87z");
}

.ft5dv1b6b {
  fill: none;
}

.il-_7smwy {
  fill: var(--svg-color--128bf4, #128bf4);
  d: path("m6.947 14.873l5.062-4.98l5.044 4.98L12.008 20z");
}

.mxawm9bvf {
  fill: var(--svg-color--e21639, #e21639);
  d: path("M6.947 8.98L12.009 4l5.044 4.98L12 14.107z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
