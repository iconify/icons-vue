<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="vgiveeuzo"/><path class="vl96s1rwg"/><path clip-rule="evenodd" class="drau0vbjn"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lpnt-background" /></template>
<style>
.drau0vbjn {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M9.067 7.2H4V20h12.8v-5.067zm6.666 11.733V16.8H7.2V8.267H5.067v10.666z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vgiveeuzo {
  fill: var(--svg-color--e82f59, #e82f59);
  d: path("M24 0H0v24h24z");
}

.vl96s1rwg {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.133 4H20v13.866l-3.2-2.933V7.2H9.068z");
}

</style>
