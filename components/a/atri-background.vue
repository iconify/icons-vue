<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="fz_tdsbuh"/><path class="r47dvxb8z"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:atri-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.fz_tdsbuh {
  fill: var(--svg-color--e01920, #e01920);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r47dvxb8z {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.333 6h1.334v2.667c0 3.555-.84 8.36-6.667 9.333v-1.778C5.333 16 9.32 14.444 9.32 8.667zm1.778 0h1.778v12h-1.778zm3.556 0h-1.334v2.667c0 3.555.84 8.36 6.667 9.333v-1.778c-1.333-.222-5.32-1.778-5.32-7.555z");
}

</style>
