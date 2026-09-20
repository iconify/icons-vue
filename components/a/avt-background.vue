<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="kucyqtb5x"/><path class="mci510agf"/><path class="aug45el2c"/><path class="ixcj73zxb"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:avt-background" /></template>
<style>
.aug45el2c {
  fill: var(--svg-color--fff, #fff);
  d: path("m19.764 8.127l-6.117 2.86L7.642 20z");
}

.ft5dv1b6b {
  fill: none;
}

.ixcj73zxb {
  fill: var(--svg-color--fff, #fff);
  d: path("m11.055 4l8.306 13.638l-4.607-2.137l-3.7-7.755z");
}

.kucyqtb5x {
  fill: var(--svg-color--1d2733, #1d2733);
  d: path("M24 0H0v24h24z");
}

.mci510agf {
  fill: var(--svg-color--fff, #fff);
  d: path("m14.867 15.502l4.517 2.146H4.871l10-2.146zM11.055 4v3.746l-6.82 8.513z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
