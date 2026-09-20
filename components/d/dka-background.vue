<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="juy3zob5x"/><path class="z2xa7smtj"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dka-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.juy3zob5x {
  fill: var(--svg-color--1fc0dc, #1fc0dc);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.z2xa7smtj {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.429 14.666c-1.808-.01-1.68-.235-2.65-1.173a74 74 0 0 0-2.843-2.661c-.565-.486-2.117-.433-2.117-.433H5.142v8.533h3.205c.714 0 1.69-.853 1.69-.853l2.486-2.63l.847.897s-1.855 1.983-2.607 2.72c-1.024 1.008-2.416.933-2.416.933H4V9.333h3.82c2.245 0 2.896.656 2.896.656s2.88 2.746 3.375 3.178c.678.544 1.563.432 1.563.432h3.205V5.067H16.18c-.085 0-.827-.038-1.573.389c-.544.219-3.008 2.901-3.008 2.901l-.89-.821s1.983-2.085 2.383-2.47C13.492 4.683 14.212 4 16.18 4h3.818v10.666z");
}

</style>
