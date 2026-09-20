<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="w-3uqwzmy"/><path class="op-16131z"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bcn-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.op-16131z {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.138 12.91a3.84 3.84 0 0 0-2.4-1.146v-.018a3.32 3.32 0 0 0 2.118-1.121c.498-.593.77-1.344.768-2.118a3.35 3.35 0 0 0-1.28-2.86c-.856-.688-2.144-.962-3.9-.962h-6.41v6.05H4v2.522h10.4c.82 0 1.43.033 1.835.36c.406.326.609.74.609 1.367c0 1.398-1.164 1.803-2.445 1.803h-3.843v-1.513H8.034v4.034h6.63c1.415.062 2.81-.274 3.97-1.085a3.59 3.59 0 0 0 1.36-3.018a3.36 3.36 0 0 0-.856-2.294m-5.118-2.174h-3.464v-3.53h3.473c1.623 0 2.435.516 2.435 1.769s-.812 1.76-2.444 1.76");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.w-3uqwzmy {
  fill: var(--svg-color--f04086, #f04086);
  d: path("M24 0H0v24h24z");
}

</style>
