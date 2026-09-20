<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="kq4dlksjf"/><path class="y_4574leu"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bond-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kq4dlksjf {
  fill: var(--svg-color--ff4339, #ff4339);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.y_4574leu {
  fill: var(--svg-color--fff, #fff);
  d: path("m8.889 16.868l-2.68 1.911A7.97 7.97 0 0 1 4 13.317v-.098a8 8 0 0 1 16 .004v.09a7.97 7.97 0 0 1-2.187 5.453l-2.702-1.916v-4.049l.987-.729l-4.071-3.08l-4.071 3.08l.933.73zM12 11.93h.067c1.208 0 2.222.893 2.15 2.027v2.266l-2.222-1.555l-2.217 1.578v-2.29c0-1.137 1.009-2.026 2.222-2.026");
}

</style>
