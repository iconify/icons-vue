<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="z8q3o4b9p"/><path clip-rule="evenodd" class="zyl_o-vwk"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:enkrypt-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.z8q3o4b9p {
  fill: var(--svg-color--c54aff, #c54aff);
  d: path("M24 0H0v24h24z");
}

.zyl_o-vwk {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M4 7.079A3.08 3.08 0 0 1 7.08 4H20v2.362c0 1.223-.99 2.213-2.213 2.213h-6.075a3.08 3.08 0 0 0-3.079 3.08v.783a3.08 3.08 0 0 0 3.08 3.079h6.074c1.222 0 2.213.99 2.213 2.213V20H7.079A3.08 3.08 0 0 1 4 16.921zm7.845 2.784h6.23c1.064 0 1.925.862 1.925 1.924v.518a1.924 1.924 0 0 1-1.924 1.924h-6.23a1.924 1.924 0 0 1-1.925-1.924v-.518c0-1.062.861-1.924 1.924-1.924");
}

</style>
