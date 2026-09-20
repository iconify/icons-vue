<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ijbtopb4e"/><path class="kuanlmwzr"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bitstamp-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ijbtopb4e {
  fill: var(--svg-color--149f49, #149f49);
  d: path("M24 0H0v24h24z");
}

.kuanlmwzr {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.747 5.498V4c.115 0 4.5.007 6.585.007c1.114.015 2.091.391 2.844 1.267c.912 1.056.984 3.307-.767 4.255c-.008.007-.102.065-.145.094c.333.217.68.383.955.637c1.773 1.577 1.18 4.385-1.114 5.217a5 5 0 0 1-1.621.304H6.76v-1.498c1.143-.275 1.708-.854 1.73-1.773c.036-1.187-.362-1.671-1.744-2.113V9.08c1.128-.253 1.73-.861 1.744-1.758c.021-.92-.543-1.513-1.744-1.824m3.444 8.56c1.05 0 2.07-.014 3.191-.014c.948-.05 1.57-.825 1.563-1.794c-.007-.905-.658-1.643-1.584-1.694c-1.02-.058-3.126-.036-3.163-.036c-.007 1.172-.007 2.374-.007 3.539m0-5.086c.97 0 1.91.036 2.844-.015c.883-.043 1.49-.71 1.549-1.563c.05-.818-.507-1.57-1.39-1.657c-.984-.087-1.99-.022-3.003-.022zm6.992 9.457V20H6.812v-1.57z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
