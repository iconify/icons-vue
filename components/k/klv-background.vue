<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="lb59vbcyz"/><path class="k7klzab2c"/><path class="sup7zacgw"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:klv-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k7klzab2c {
  fill: var(--svg-color--fff, #fff);
  d: path("M20 19.714H4V4.286z");
}

.lb59vbcyz {
  fill: var(--svg-color--fff, #fff);
  d: path("M20 19.714h-7.703L20 12.285z");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.sup7zacgw {
  fill: var(--svg-color--fff, #fff);
  d: path("M20 19.714L16.148 16l.89-.857z");
  opacity: var(--svg-opacity--0-14, 0.14);
}

</style>
