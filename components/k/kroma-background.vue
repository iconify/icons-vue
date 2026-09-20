<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="i4v9bxotf"/><path class="cs2l74bwj"/><path class="yls4-kbgd"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kroma-background" /></template>
<style>
.cs2l74bwj {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 4.333L4 9.444L8 12l4-2.556L16 12l4-2.556z");
}

.ft5dv1b6b {
  fill: none;
}

.i4v9bxotf {
  fill: var(--svg-color--7ae03a, #7ae03a);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.yls4-kbgd {
  fill: var(--svg-color--fff, #fff);
  d: path("m20 9.444l-8 5.111l-8-5.11v5.11l8 5.112l8-5.112z");
}

</style>
