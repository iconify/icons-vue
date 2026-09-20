<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="eucedkani"/><path class="o6ehfr5md"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:flr-background" /></template>
<style>
.eucedkani {
  fill: var(--svg-color--e62058, #e62058);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.o6ehfr5md {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.028 10.07H8.05c-2.19 0-3.989 1.66-4.044 3.762c0 .055.044.1.11.1H12.1c2.19.01 3.99-1.661 4.044-3.763a.11.11 0 0 0-.11-.1zM19.889 4H7.995A3.92 3.92 0 0 0 4 7.764a.1.1 0 0 0 .1.1H16A3.93 3.93 0 0 0 20 4.1c0-.055-.05-.1-.105-.1zM5.931 20a1.931 1.931 0 1 0 0-3.862a1.931 1.931 0 0 0 0 3.862");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
