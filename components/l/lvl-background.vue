<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="jfokftkbo"/><path class="ofgvlt13s"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lvl-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jfokftkbo {
  fill: var(--svg-color--ffb313, #ffb313);
  d: path("M24 0H0v24h24z");
}

.ofgvlt13s {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.032 4h5.162v3.613H5.032zm0 6.194h8.774v3.612H5.032zm0 6.193h13.936V20H5.032z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
