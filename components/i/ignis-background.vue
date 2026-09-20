<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="wn1kn-byg"/><path class="p4s02acbr"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ignis-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.p4s02acbr {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.46 6.252L10.975 4l-2.667 6.736l1.707 3.11zm2.463 3.697l-2.03-3.438l-7.816 13.456h3.918zm-2.289 4.718L11.59 20l4.923-2.92z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.wn1kn-byg {
  fill: var(--svg-color--f9c011, #f9c011);
  d: path("M24 0H0v24h24z");
}

</style>
