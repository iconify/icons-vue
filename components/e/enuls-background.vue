<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="dyd4hr93x"/><path class="awa_-bcok"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:enuls-background" /></template>
<style>
.awa_-bcok {
  fill: var(--svg-color--000, #000);
  d: path("m10.689 14.46l1.313 1.82V20L7.2 17.945V8.26c0-.351.138-.687.384-.935c.246-.249.58-.388.928-.388l4.625 6.418l2.354 1.445V6.816l-2.177-.931v5.464l-1.312-1.822V4L16.8 6.058v8.983c0 .35-.138.687-.384.935s-.58.388-.928.388l-3.338-2.13l-3.636-5.047v7.997l2.175.93z");
}

.dyd4hr93x {
  fill: var(--svg-color--00e789, #00e789);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
