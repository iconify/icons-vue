<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="pbwid1bnl"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:fuel-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.pbwid1bnl {
  fill: var(--svg-color--00f58c, #00f58c);
  d: path("M4.72 4h10.574l-7.005 7.005a.928.928 0 0 1-1.493-.26L4.082 5.008A.706.706 0 0 1 4.72 4M4 20v-6.815a.66.66 0 0 1 .659-.659h6.815zm9.21-9.21a1.66 1.66 0 0 1-1.174.486H9.78l6.79-6.79A1.66 1.66 0 0 1 17.743 4H20z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
