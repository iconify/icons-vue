<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="dc6cnk8kb"/><path class="mjmwmrv3r"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bybit-background" /></template>
<style>
.dc6cnk8kb {
  fill: var(--svg-color--f6a500, #f6a500);
  d: path("M15.403 13.445V9.334h.827v4.111z");
}

.ft5dv1b6b {
  fill: none;
}

.mjmwmrv3r {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.772 14.666H4v-4.111h1.7c.827 0 1.308.45 1.308 1.155a.95.95 0 0 1-.523.85a.96.96 0 0 1 .582.923c0 .768-.54 1.183-1.295 1.183m-.137-3.395h-.81v.947h.81c.35 0 .546-.19.546-.474c0-.282-.196-.473-.546-.473m.053 1.668h-.862v1.011h.862c.374 0 .553-.23.553-.507c0-.278-.179-.502-.553-.502zm3.901.041v1.686h-.821V12.98l-1.272-2.425h.898l.79 1.657l.78-1.657h.897zm3.615 1.686h-1.772v-4.111h1.701c.827 0 1.308.45 1.308 1.155a.95.95 0 0 1-.524.85a.96.96 0 0 1 .583.923c0 .768-.541 1.183-1.296 1.183m-.137-3.395h-.809v.947h.81c.35 0 .546-.19.546-.474c0-.282-.196-.473-.547-.473m.053 1.668h-.862v1.011h.862c.375 0 .553-.23.553-.507c0-.278-.178-.502-.553-.502zm5.773-1.669v3.396h-.825v-3.395H16.96v-.716H20v.716z");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
