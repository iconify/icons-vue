<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="peoil5bac"/><path class="y34x20-0v"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cng-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.peoil5bac {
  fill: var(--svg-color--0ff, #0ff);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.y34x20-0v {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.5 6.43v5.07l2-1.25V5zm2.93 4.695L13 13l2.5 1.5l4.5-2.605l-1.38-.8a2.14 2.14 0 0 0-2.19.03m-.93 5.125l-4-2.75v2.75l4 2.75zm-5 .115V12.5l-2 1V19l1.085-.755c.645-.42.915-1.09.915-1.88m.67-5.435L8.69 9.5L4 12.355l2.205 1.43zm1.33-2.98L8 5v1.85c0 .62.325 1.195.85 1.5l3.65 2.175z");
}

</style>
