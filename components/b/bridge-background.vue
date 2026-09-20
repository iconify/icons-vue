<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ucwmfmb4u"/><path class="pvfdjdbvs"/><path class="i41_7vkpa"/><path class="nmu4s7xgs"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bridge-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i41_7vkpa {
  fill: var(--svg-color--fff, #fff);
  d: path("m16.85 12.004l-1.214 1.21l-1.815 1.814h-.005l-1.205-1.2l-.004-.01v-.01l1.82-1.81L18.78 7.64l.01-.003q.006 0 .01.003l1.2 1.2v.02l-3.14 3.15zm-7.268-.005l-1.21 1.22l-3.149 3.139h-.01l-1.21-1.2l-.002-.004L4 15.15v-.004l.003-.003l3.14-3.15l1.214-1.214l1.815-1.8v-.005l.005-.001l.005.001l1.205 1.205v.01l-1.81 1.815z");
}

.nmu4s7xgs {
  fill: var(--svg-color--fff, #fff);
  d: path("m9.582 12l6.778 6.778v.015l-1.2 1.2l-.004.001l-.005-.001l-6.779-6.773zm7.268.005L20 15.149v.015l-1.205 1.2l-.005.001l-.005-.001l-3.15-3.145l1.21-1.21h.01zm-9.213 6.772l2.54-2.54l.003-.002h.008l.004.003l1.2 1.204h.004v.005l.002.005l-.002.005l-2.54 2.535h-.01l-1.209-1.2v-.005l-.001-.005z");
}

.pvfdjdbvs {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.636 10.784L14.421 12L7.638 5.22v-.015l1.2-1.2h.02zm.73-5.574l-1.21-1.204h-.01l-2.54 2.54v.01l1.205 1.209h.015l2.54-2.545zm-8.003 5.569l-1.21 1.22l-3.14-3.14l-.002-.003v-.009l.003-.003l1.2-1.2h.014l3.14 3.14z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.ucwmfmb4u {
  fill: var(--svg-color--0050ff, #0050ff);
  d: path("M24 0H0v24h24z");
}

</style>
