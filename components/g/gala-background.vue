<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="fsp4-m6-f"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gala-background" /></template>
<style>
.fsp4-m6-f {
  fill: var(--svg-color--fff, #fff);
  d: path("m5.5 7.5l6.52 4.005l2.5-1.49L13.5 9.5l-1.39.895L7.41 7.5l4.52-2.415l5.63 3.11l1-.595L12.02 4zM6 8.76l-1-.635V15.8l6.5 4.2v-7.935L9 10.5v1.205l1.5.97v5.39L6 15.18zm6.5 9.97v1.265l6.5-4.17V8.15l-6.5 3.915v3.04l1-.645V12.7L18 10v5.21l-5.5 3.525z");
}

.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
