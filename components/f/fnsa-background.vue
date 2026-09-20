<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="wv9gardxe"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:fnsa-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.wv9gardxe {
  fill: var(--svg-color--fff, #fff);
  d: path("M18 6h-5.855C8.695 6 6 8.63 6 12.025V20H4v-7.975C4 7.59 7.65 4 12.145 4H20v7.975C20 16.41 16.35 20 11.855 20H7.5v-8.335A5.01 5.01 0 0 1 12.43 7.5H16v2h-3.335c-1.505 0-2.57.625-3 2H16v2H9.5V18h2.355C15.305 18 18 15.37 18 11.975z");
}

</style>
