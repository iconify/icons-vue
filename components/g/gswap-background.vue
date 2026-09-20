<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="s6ecz8bsg"/><path class="ectha6lzd"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gswap-background" /></template>
<style>
.ectha6lzd {
  fill: var(--svg-color--fff, #fff);
  d: path("m17.25 7.5l.5-2H9c-.665 0-2.1.4-2.5 2L6 11h1.75l.5-2.5c0-.335.25-1 1.25-1zm0 0l-.25 2H9.75L9.5 11H20zm-10.5 9l-.5 2H15c.665 0 2.1-.4 2.5-2L18 13h-1.75l-.5 2.5c0 .335-.25 1-1.25 1zm0 0l.25-2h7.25l.25-1.5H4z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.s6ecz8bsg {
  fill: var(--svg-color--7377d8, #7377d8);
  d: path("M24 0H0v24h24z");
}

</style>
