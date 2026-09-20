<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="pjg92jbzf"/><path class="alkt3rbtk"/><path class="fxw0xbc5g"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:coinex-smart-chain-background" /></template>
<style>
.alkt3rbtk {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.2 9.303a2.77 2.77 0 0 1 2.932 1.247a2.75 2.75 0 0 1-1.598 4.096a2.77 2.77 0 0 1-3.006-1.06a2.75 2.75 0 0 1-.507-1.59H9.58a5.2 5.2 0 0 0 1.057 3.144a5.21 5.21 0 0 0 6.066 1.697a5.2 5.2 0 0 0 2.541-2.138a5.19 5.19 0 0 0-.65-6.254a5.21 5.21 0 0 0-6.21-1.057A5.2 5.2 0 0 1 14.2 9.303");
}

.ft5dv1b6b {
  fill: none;
}

.fxw0xbc5g {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.8 14.698a2.77 2.77 0 0 1-2.933-1.248a2.75 2.75 0 0 1 1.598-4.097a2.77 2.77 0 0 1 3.007 1.06a2.75 2.75 0 0 1 .507 1.591h2.442c0-1.135-.37-2.24-1.057-3.144a5.22 5.22 0 0 0-8.607.441a5.19 5.19 0 0 0 .65 6.254a5.214 5.214 0 0 0 6.21 1.057a5.2 5.2 0 0 1-1.816-1.914");
}

.pjg92jbzf {
  fill: var(--svg-color--5f5fff, #5f5fff);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
