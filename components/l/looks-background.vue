<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="cst7j0b1b"/><path clip-rule="evenodd" class="qeetuzbhz"/><path clip-rule="evenodd" class="cia-fxytu"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:looks-background" /></template>
<style>
.cia-fxytu {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M14.667 10.668a2.667 2.667 0 1 0-5.334 0a2.667 2.667 0 0 0 5.334 0m-1.334 0A1.333 1.333 0 0 0 12 9.334c-.742 0-1.333.591-1.333 1.334c0 .742.59 1.333 1.333 1.333c.742 0 1.333-.591 1.333-1.333");
}

.cst7j0b1b {
  fill: var(--svg-color--04cd58, #04cd58);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qeetuzbhz {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("m20 10.444l-4.8-4.667H8.8L4 10.444l8 7.778zm-2.222.222s-5.316-8-11.556 0c6.222 8 11.556 0 11.556 0");
}

</style>
