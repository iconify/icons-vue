<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="j48zzvbrj"/><path class="nz1_67ahw"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dtx-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.j48zzvbrj {
  fill: var(--svg-color--78e6d0, #78e6d0);
  d: path("M24 0H0v24h24z");
}

.nz1_67ahw {
  fill: var(--svg-color--fff, #fff);
  d: path("m19.08 9.601l-3.252 2.393a3.65 3.65 0 0 0-.771-2.24c-1.272-1.647-3.672-1.976-5.36-.735L4 13.209l.92 1.19l3.252-2.393c.001.812.272 1.6.77 2.24c1.273 1.647 3.673 1.976 5.362.735L20 10.791zm-5.643 4.258a2.44 2.44 0 0 1-2.648.147a2.35 2.35 0 0 1-.939-.995a2.3 2.3 0 0 1-.213-1.335c.066-.458.27-.885.582-1.226c.317-.345.729-.59 1.183-.704a2.44 2.44 0 0 1 1.385.056c.443.15.832.428 1.12.797a2.285 2.285 0 0 1 .148 2.586c-.16.263-.37.492-.618.674");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
