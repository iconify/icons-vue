<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="r-ccveeoj"/><path clip-rule="evenodd" class="po9qfyb9t"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cho-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.po9qfyb9t {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M20 12a8 8 0 1 1-16 0a8 8 0 0 1 16 0M7.765 12c0-1.177.941-3.294 4.235-3.294s4.235 2.117 4.235 3.294c0 1.176-1.02 3.294-4.235 3.294c-3.374 0-4.235-2.118-4.235-3.294");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r-ccveeoj {
  fill: var(--svg-color--1c4c06, #1c4c06);
  d: path("M24 0H0v24h24z");
}

</style>
