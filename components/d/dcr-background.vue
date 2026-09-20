<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="krjf-to1p"/><path class="hmzbctbnq"/><path class="jet5z0b8o"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dcr-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hmzbctbnq {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.038 13.453h3.957c1.415-.01 2.664-1.151 2.659-2.594c.005-1.443-1.244-2.85-2.659-2.859h-1.262l-2.695-2h3.957a5.13 5.13 0 0 1 3.182 1.113a4.8 4.8 0 0 1 1.724 2.812a4.72 4.72 0 0 1-.503 3.247a5 5 0 0 1-2.523 2.2L20 18h-3.58z");
}

.jet5z0b8o {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.014 10.5h3.94L7.58 6H4l3.125 2.628a4.98 4.98 0 0 0-2.52 2.197c-1.129 2.027-.585 4.617 1.219 6.06A5.12 5.12 0 0 0 9.014 18h3.949l-2.695-2H9.014c-1.799-.006-3.201-2.123-2.468-3.848c.398-.938 1.438-1.649 2.468-1.652");
}

.krjf-to1p {
  fill: var(--svg-color--2970ff, #2970ff);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
