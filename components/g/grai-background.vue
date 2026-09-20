<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="hobsdabop"/><path class="u64veyu_k"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:grai-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hobsdabop {
  fill: var(--svg-color--a101f8, #a101f8);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.u64veyu_k {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.126 14.105a4.633 4.633 0 0 1-7.63.927a1.36 1.36 0 0 0-1.01-.506c-.83 0-1.38.842-.884 1.504A6.737 6.737 0 0 0 18.4 14.105h.758a.842.842 0 0 0 0-1.684h-3.79a.842.842 0 1 0 0 1.684zm.388-4.631c-.392 0-.754-.207-1.01-.505a4.632 4.632 0 0 0-7.63.926h.758a.842.842 0 1 1 0 1.684h-3.79a.842.842 0 1 1 0-1.684H5.6A6.737 6.737 0 0 1 17.398 7.97c.497.66-.05 1.503-.884 1.503");
}

</style>
