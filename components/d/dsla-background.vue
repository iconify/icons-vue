<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="pjf-fpx9p"/><path class="jllerzbmn"/><path class="na41raczh"/><path class="m8efx4bpv"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dsla-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.jllerzbmn {
  fill: var(--svg-color--f69d88, #f69d88);
  d: path("M13.005 4.545h-2.002a6.45 6.45 0 0 0-6.453 6.457v2.002a6.445 6.445 0 0 0 6.448 6.449h2.003a6.445 6.445 0 0 0 6.448-6.448v-2.003A6.445 6.445 0 0 0 13 4.554z");
}

.m8efx4bpv {
  fill: var(--svg-color--f0f3fa, #f0f3fa);
  d: path("m15.092 6.708l-2.25 3.846l2.21 1.332l-6.135 5.408l2.223-3.869l-2.223-1.292z");
}

.na41raczh {
  fill: var(--svg-color--2196f3, #2196f3);
  d: path("M12.005 19.305a7.304 7.304 0 1 0 0-14.609a7.304 7.304 0 0 0 0 14.61");
}

.pjf-fpx9p {
  fill: var(--svg-color--ffe1a5, #ffe1a5);
  d: path("m5.636 7.536l-.689 1.178a7.07 7.07 0 0 0 2.59 9.66l1.177.679a7.07 7.07 0 0 0 9.66-2.59l.679-1.177a7.07 7.07 0 0 0-.515-7.84a7.1 7.1 0 0 0-2.074-1.82l-1.178-.679a7.07 7.07 0 0 0-9.66 2.59z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
