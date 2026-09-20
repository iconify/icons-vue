<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="vjqbjr7iv"/><path clip-rule="evenodd" class="cdpxfh-bh"/><path class="sizx9jbcu"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:fantom-background" /></template>
<style>
.cdpxfh-bh {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M11.974 4L7.202 6.708V17.21L11.974 20l4.828-2.789V6.708zm.028.8L8.4 6.96l3.6 2.1l3.6-2.1zM8 7.6v3.6l3.2-1.792zm4.4 2.6v3.6l3.2-1.792zM16 7.6v3.6l-3.2-1.792zm-4.4 2.598V13.8l-3.2-1.793zM8 12.625V16.8l4 2.398l4.001-2.4v-4.176l-4 2.178z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.sizx9jbcu {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.2 18.076V15.6H6v2.08l2 1.032v.888zM18.8 5.924V8.4H18V6.32l-2-1.03V4.4z");
}

.vjqbjr7iv {
  fill: var(--svg-color--26b6ea, #26b6ea);
  d: path("M24 0H0v24h24z");
}

</style>
