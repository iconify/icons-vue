<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path clip-rule="evenodd" class="oroq4abyc"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:hft-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.oroq4abyc {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M8.235 6.353H5.882v3.294H4v1.882h1.882v1.412H4v1.882h1.882v2.824h2.353v-2.824h7.53v2.824h2.353v-2.824H20v-1.882h-1.882v-1.412H20V9.647h-1.882V6.353h-2.353v3.294h-7.53zm7.53 6.588v-1.412h-7.53v1.412z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
