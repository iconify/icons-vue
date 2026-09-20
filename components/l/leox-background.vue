<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="wobqfwbww"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:leox-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.wobqfwbww {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.688 16.138a.486.486 0 1 0 0-.971a.486.486 0 0 0 0 .971m1.797-1.456h.043a.35.35 0 0 0 .258-.112l5.078-5.084a.37.37 0 0 0 .107-.271a.364.364 0 0 0-.364-.36a.37.37 0 0 0-.267.107l-4.75 4.749a5.5 5.5 0 0 1-.68-2.656c0-3.04 2.477-5.356 5.507-5.356a5.5 5.5 0 0 1 3.049.908a.37.37 0 0 0 .47-.043L17.72 4.63a.37.37 0 0 0-.248-.63a.4.4 0 0 0-.277.107L15.55 5.8a5.9 5.9 0 0 0-3.127-.83c-3.447 0-6.248 2.636-6.248 6.084c0 1.238.359 2.432 1.044 3.462c.063.092.16.15.271.165zm10.05-7.138a.379.379 0 0 0-.674.174a.36.36 0 0 0 .072.273a5.42 5.42 0 0 1 1.136 3.297a5.633 5.633 0 0 1-5.583 5.603c-.962 0-1.928-.34-2.758-.792l4.593-4.67a.37.37 0 0 0 .107-.248a.4.4 0 0 0-.107-.277a.38.38 0 0 0-.291-.107a.4.4 0 0 0-.243.107l-8.478 8.483a.374.374 0 0 0 .53.524l3.335-3.273a6.44 6.44 0 0 0 3.273.957c3.496 0 6.35-2.865 6.35-6.312c0-1.36-.436-2.656-1.262-3.739");
}

</style>
