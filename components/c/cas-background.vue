<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mwuu7kdta"/><path clip-rule="evenodd" class="aqd5lhccb"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cas-background" /></template>
<style>
.aqd5lhccb {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M10.586 4h-1.88v2.845a6.11 6.11 0 0 0-2.824 5.156a6.11 6.11 0 0 0 2.824 5.156V20h1.88v-2.046a6.14 6.14 0 0 0 2.826 0V20h1.882v-2.843q.508-.326.941-.741v1.703h1.883V6.353h-1.883v1.233a6 6 0 0 0-.94-.74V4h-1.883v2.047a6.14 6.14 0 0 0-2.826.001zm5.65 8a4.235 4.235 0 1 0-8.471 0a4.235 4.235 0 0 0 8.47 0");
}

.ft5dv1b6b {
  fill: none;
}

.mwuu7kdta {
  fill: var(--svg-color--0723a1, #0723a1);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
