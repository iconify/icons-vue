<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="bd-426bdc"/><path class="ltw-6bb4c"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:avax-background" /></template>
<style>
.bd-426bdc {
  fill: var(--svg-color--e84142, #e84142);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.ltw-6bb4c {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.015 19h-2.69c-.565 0-.845 0-1.015-.105a.67.67 0 0 1-.31-.53c-.01-.2.13-.44.41-.925L11.05 5.9c.285-.49.43-.735.61-.825c.19-.1.425-.1.62 0c.18.09.32.335.6.825l1.37 2.35l.005.01q.338.502.53 1.075c.075.3.075.625 0 .93c-.126.384-.304.75-.53 1.085l-3.49 6.08l-.01.02a4.4 4.4 0 0 1-.68 1a2.1 2.1 0 0 1-.825.475C8.965 19 8.65 19 8.015 19m6.795 0h3.85c.575 0 .86 0 1.03-.11c.185-.12.3-.315.31-.53c.01-.195-.126-.425-.395-.88l-.03-.05l-1.93-3.25l-.02-.04c-.27-.45-.41-.68-.585-.77a.67.67 0 0 0-.615 0c-.18.09-.32.33-.6.81l-1.93 3.255v.01c-.285.48-.425.72-.415.915c.01.215.125.415.31.535c.165.105.45.105 1.02.105");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
