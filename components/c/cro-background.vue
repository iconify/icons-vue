<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="bftj-bcvz"/><path class="y84ppjbpr"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cro-background" /></template>
<style>
.bftj-bcvz {
  fill: var(--svg-color--2e4b9f, #2e4b9f);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.y84ppjbpr {
  fill: var(--svg-color--fff, #fff);
  d: path("m8.121 4.727l-.97 4.364h9.698l-.97-4.364zM9.091 12l-2.137-1.45L4 12.484l3.949 6.788h1.495l1.586-1.82v-.825l-1.94-1.762zm5.7-1.94H9.394l1.15 1.94l-.53 2.424h4.162L13.455 12zm.118 1.94l2.136-1.655L20 12.485l-3.893 6.788H14.67l-1.714-1.833v-.847l1.954-1.805z");
}

</style>
