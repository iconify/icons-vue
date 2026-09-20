<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="gayp2ab_d"/><path class="gb-34ebfd"/><path clip-rule="evenodd" class="crv5e9d5d"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bld-background" /></template>
<style>
.crv5e9d5d {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M20 7.077h-9.846v9.846H20zm-3.282 3.282h-3.282v3.282h3.282z");
}

.ft5dv1b6b {
  fill: none;
}

.gayp2ab_d {
  fill: var(--svg-color--bb2d40, #bb2d40);
  d: path("M24 0H0v24h24z");
}

.gb-34ebfd {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 10.36h3.282v3.282H4z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
