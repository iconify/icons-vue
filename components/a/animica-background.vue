<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="tonn9tbtm"/><path clip-rule="evenodd" class="gedlcgtyu"/><path class="p_g1r50xs"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:animica-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gedlcgtyu {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 4a8 8 0 1 0 0 16a8 8 0 0 0 0-16m0 1.571a6.429 6.429 0 1 1 0 12.858a6.429 6.429 0 0 1 0-12.858");
}

.p_g1r50xs {
  fill: var(--svg-color--fff, #fff);
  d: path("m12 7.679l3.071 8.928H8.929z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.tonn9tbtm {
  fill: var(--svg-color--2e63ff, #2e63ff);
  d: path("M24 0H0v24h24z");
}

</style>
