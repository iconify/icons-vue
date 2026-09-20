<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="uzs4kbcpc"/><path class="p4g--m_2w"/><path class="vbkup0eic"/><path class="vs50qebvw"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cbeth-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.p4g--m_2w {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 19.25a7.25 7.25 0 1 0 0-14.5a7.25 7.25 0 0 0 0 14.5M20 12a8 8 0 1 1-16 0a8 8 0 0 1 16 0");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.uzs4kbcpc {
  fill: var(--svg-color--0052ff, #0052ff);
  d: path("M24 0H0v24h24z");
}

.vbkup0eic {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 6v4.25l3.5 1.605zm0 0l-3.5 5.855l3.5-1.6zm0 8.61v2.89l3.5-4.975zm0 2.89v-2.89l-3.5-2.085zm0-3.555l3.5-2.09l-3.5-1.6z");
}

.vs50qebvw {
  fill: var(--svg-color--fff, #fff);
  d: path("m8.5 11.855l3.5 2.09V10.25z");
}

</style>
