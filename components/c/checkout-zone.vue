<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="go27ylbnz"/><path class="kixw4pzrt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:checkout-zone" /></template>
<style>
.go27ylbnz {
  d: path("M2.5 6.5v-2a2 2 0 0 1 2-2h2m11 0h2a2 2 0 0 1 2 2v2m0 11v2a2 2 0 0 1-2 2h-2m-11 0h-2a2 2 0 0 1-2-2v-2m8-15h3m-3 19h3m-11-11v3m19-3v3M8 6h1.5A1.5 1.5 0 0 1 11 7.5A1.5 1.5 0 0 1 9.5 9H8a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 8 6m.75 3v1.5m-.443 0h7.386a1.5 1.5 0 0 1 1.413.995l.269.755A1.31 1.31 0 0 1 16.142 14H7.858a1.31 1.31 0 0 1-1.233-1.75l.269-.755a1.5 1.5 0 0 1 1.413-.995");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kixw4pzrt {
  d: path("M7.5 14h9a1.5 1.5 0 0 1 1.5 1.5v1a1.5 1.5 0 0 1-1.5 1.5h-9A1.5 1.5 0 0 1 6 16.5v-1A1.5 1.5 0 0 1 7.5 14m6.25-1.75h.01M8.5 16h3");
}

</style>
