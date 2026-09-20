<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="m-379bbuk"/><path class="faq5f2b8u"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lzm-background" /></template>
<style>
.faq5f2b8u {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.733 12.907L4 7.467v12.266h10.667l-2.4-3.2H7.733zm.534-8.64l4 6.666l4-6.666H20v15.466h-3.733v-9.6l-4 6.4L4 4.267z");
}

.ft5dv1b6b {
  fill: none;
}

.m-379bbuk {
  fill: var(--svg-color--36a4de, #36a4de);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
