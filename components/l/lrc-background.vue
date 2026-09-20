<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="vmfev6bhz"/><path class="anav68jbm"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lrc-background" /></template>
<style>
.anav68jbm {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.326 5.882v12.237L4 13.773zm.001 12.236l5.026-4.345l-1.462-2.296H20z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vmfev6bhz {
  fill: var(--svg-color--1f63ff, #1f63ff);
  d: path("M24 0H0v24h24z");
}

</style>
