<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="tr-_w6b1b"/><path class="ulowdybsq"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:inv-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.tr-_w6b1b {
  fill: var(--svg-color--5a86e7, #5a86e7);
  d: path("M24 0H0v24h24z");
}

.ulowdybsq {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 7.755c0-.65.45-1.81 1-2.255v13H4zM13 5.5h1v11.975a5.65 5.65 0 0 0 3.57-1.7c.92-1 1.43-2.315 1.43-3.275v-6h-2v5.75c0 .65-.45 1.805-1 2.25v-9h4v7c0 1.27-.615 2.765-1.68 3.93A6.23 6.23 0 0 1 14 18.48v.02h-1V6.52c-1.45.13-2.65.82-3.5 1.71c-.945 1-1.5 2.31-1.5 3.27v6h2v-5.75c0-.65.45-1.805 1-2.25v9H7v-7c0-1.275.63-2.765 1.73-3.93C9.85 6.39 11.53 5.5 13 5.5");
}

</style>
