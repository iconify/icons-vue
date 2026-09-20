<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="v1zwv257l"/><path class="xcz_2mrgn"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:eusd-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.v1zwv257l {
  fill: var(--svg-color--90c31f, #90c31f);
  d: path("M24 0H0v24h24z");
}

.xcz_2mrgn {
  fill: var(--svg-color--fff, #fff);
  d: path("M20 6.823H8.936c-.602.015-1.929.556-2.432 2.636c0 .113-.142.771-.33 1.6H4l1.708 2.023l-.263 1.11c-.292.994-.306 2.984 1.971 2.984h9.445c.452 0 .852-.291.979-.715l.358-1.167h-7.412c-.574 0-.974-.546-.974-1.101s.4-1.252.974-1.252h6.922c.424 0 .796 0 .923-.395l.494-1.487h-7.247a1.21 1.21 0 0 1-1.214-1.196a1.176 1.176 0 0 1 1.214-1.157h6.804a1.035 1.035 0 0 0 .98-.734z");
}

</style>
