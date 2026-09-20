<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="aib6c2tlk"/><path class="cb2v_kbjk"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:glc-background" /></template>
<style>
.aib6c2tlk {
  fill: var(--svg-color--ffca3b, #ffca3b);
  d: path("M24 0H0v24h24z");
}

.cb2v_kbjk {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.423 15.442a7.317 7.317 0 0 0 13.575-1.76L20 11.995a.46.46 0 0 0-.452-.451H14.51a.46.46 0 0 0-.452.451v1.387c0 .243.201.441.443.446h2.803c-.359.883-.983 1.848-1.787 2.361a4.6 4.6 0 0 1-2.482.723v.006a4.98 4.98 0 0 1-4.124-2.176h.802a.686.686 0 1 0 0-1.372H8.26a4.9 4.9 0 0 1-.123-2.285h1.577a.686.686 0 0 0 0-1.372h-1.11l.002-.004h-.008a4.96 4.96 0 0 1 6.576-2.2a4.94 4.94 0 0 1 1.727 1.393a.41.41 0 0 0 .638.032l1.018-1.084a.44.44 0 0 0 .025-.579c-1.349-1.615-3.435-2.586-5.704-2.586a7.32 7.32 0 0 0-6.95 5.028H4.686a.686.686 0 1 0 0 1.372h.94a9 9 0 0 0-.046.706q-.021.747.105 1.485h-.01l.017.094H4.686a.686.686 0 0 0 0 1.372h1.412q.144.359.325.7");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
