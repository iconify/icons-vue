<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="e04xsnbce"/><path class="zlreewvwc"/><path clip-rule="evenodd" class="l4mgn3bow"/><path class="do9xlxrbx"/><path class="i2k8y279u"/><path class="ktaqf-d5q"/><path clip-rule="evenodd" class="sqjyw093f"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:fida-background" /></template>
<style>
.do9xlxrbx {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.793 11.878h.409v8h-.409z");
}

.e04xsnbce {
  fill: var(--svg-color--8081ee, #8081ee);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.i2k8y279u {
  fill: var(--svg-color--fff, #fff);
  d: path("m12.252 11.879l-.21.345L5.09 8.245L5.3 7.9z");
}

.ktaqf-d5q {
  fill: var(--svg-color--fff, #fff);
  d: path("m11.79 11.879l.21.345l6.947-3.979l-.21-.345z");
}

.l4mgn3bow {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M8.21 9.907L12 7.789l3.79 2.118v4.19L12 16.21l-3.79-2.114zm.422.185L12 8.21l3.368 1.882v3.722l-3.364 1.975l-3.372-1.975z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.sqjyw093f {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M4.842 8.021L12 4l7.158 4.021v7.962L12 20l-7.158-4.017zm.421.19L12 4.42l6.737 3.79v7.579L12 19.579l-6.737-3.79z");
}

.zlreewvwc {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.802 4.278h.409v3.663h-.409zM8.27 13.865l.215.35l-3.095 1.852l-.21-.345zm7.52.064l-.21.35l3.141 1.881l.21-.345z");
}

</style>
