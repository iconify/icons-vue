<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="e124kab2p"/><path class="v32vbobws"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:avinoc-background" /></template>
<style>
.e124kab2p {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.887 4.941h6.4l-2.518 1.412H8.8L5.6 12l3.2 5.647h6.4L18.17 12L16.8 9.647l.23-2.823L20 12l-3.887 7.059H7.887L4 12z");
}

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

.v32vbobws {
  fill: var(--svg-color--fff, #fff);
  d: path("m7.887 10.588l8.456-5.647l-1.143 9.883l-2.287-4.236z");
}

</style>
