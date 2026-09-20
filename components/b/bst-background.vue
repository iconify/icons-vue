<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="frah4wbop"/><path class="zv1d1hbvr"/><path class="tvpkfn2kl"/><path class="r8f3jboso"/><path class="jktgl8brd"/><path class="m9epfd8xc"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bst-background" /></template>
<style>
.frah4wbop {
  fill: var(--svg-color--ffbc00, #ffbc00);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.jktgl8brd {
  fill: var(--svg-color--000, #000);
  d: path("M12 11a1 1 0 0 0-1 1h-1a2 2 0 1 1 4 0h-1a1 1 0 0 0-1-1");
}

.m9epfd8xc {
  fill: var(--svg-color--000, #000);
  d: path("M13 12a1 1 0 0 0-1-1v-1a2 2 0 0 1 0 4v-1a1 1 0 0 0 1-1");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r8f3jboso {
  fill: var(--svg-color--000, #000);
  d: path("M12 9a3 3 0 1 0 0 6v1a4 4 0 1 1 0-8zm1.305 5.702c.515-.25.949-.641 1.25-1.129l.85.525c-.4.65-.977 1.171-1.664 1.504z");
}

.tvpkfn2kl {
  fill: var(--svg-color--000, #000);
  d: path("M12 7a5 5 0 0 0-5 5H6a6 6 0 0 1 6-6zm4.645 3.145a5 5 0 0 0-1.101-1.672l.708-.706a6 6 0 0 1 1.321 2.007zM7 12.001a5 5 0 1 0 10 0h1a6 6 0 0 1-12 0zM15 12a3 3 0 0 0-3-3V8a4 4 0 0 1 4 4z");
}

.zv1d1hbvr {
  fill: var(--svg-color--000, #000);
  d: path("M5 12a7 7 0 0 0 7 7v1a8 8 0 0 1-8-8zm14 0a7 7 0 0 0-7-7V4a8 8 0 1 1 0 16v-1a7 7 0 0 0 7-7M9.52 5.452a7 7 0 0 0-2.312 1.445l-.685-.729a8 8 0 0 1 2.642-1.651z");
}

</style>
