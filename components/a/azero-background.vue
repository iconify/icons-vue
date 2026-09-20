<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="hren2tezn"/><path clip-rule="evenodd" class="nqgvtl7fz"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:azero-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hren2tezn {
  fill: var(--svg-color--1d242c, #1d242c);
  d: path("M24 0H0v24h24z");
}

.nqgvtl7fz {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("m10.571 4.377l-2.691 6.29h-3.7a.18.18 0 0 0-.18.182v1.769c0 .1.08.182.18.182h2.787L4.11 19.476a.183.183 0 0 0 .165.257H6.45a.18.18 0 0 0 .166-.112l5.36-12.979l5.287 12.978a.18.18 0 0 0 .166.113h2.297c.13 0 .216-.135.165-.257L17.055 12.8h2.765c.1 0 .18-.082.18-.182v-1.77a.18.18 0 0 0-.18-.181h-3.67l-2.672-6.29a.18.18 0 0 0-.165-.11h-2.576a.18.18 0 0 0-.165.11");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
