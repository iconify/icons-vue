<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="d3lgv0b7v"/><path class="l9jvnw3qd"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:husd-background" /></template>
<style>
.d3lgv0b7v {
  fill: var(--svg-color--1a61f0, #1a61f0);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.l9jvnw3qd {
  fill: var(--svg-color--fff, #fff);
  d: path("M18 20h-3v-5.06c0-.811-.729-1.44-1.57-1.44H9.048C7.365 13.5 6 12.155 6 10.533V4.002h3v5.061c0 .81.729 1.437 1.57 1.437h4.381c1.683.002 3.046 1.348 3.047 2.97zm-9 0H6v-5c1.683 0 3 1.38 3 3.003zm6-16h3v5c-1.684 0-3-1.379-3-3z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
