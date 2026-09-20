<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ztk7qxroc"/><path class="fapha1b2d"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:canto-background" /></template>
<style>
.fapha1b2d {
  fill: var(--svg-color--000, #000);
  d: path("M7.143 4h12.571v16H7.143v-2.857H4.286V6.857h2.857zm9.714 2.857H10v2.857H7.143v4.572H10v2.857h6.857v-2.857H10V9.714h6.857z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.ztk7qxroc {
  fill: var(--svg-color--74f8a2, #74f8a2);
  d: path("M24 0H0v24h24z");
}

</style>
