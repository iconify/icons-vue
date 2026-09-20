<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path clip-rule="evenodd" class="wu6mjgapn"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:eosdt-background" /></template>
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

.wu6mjgapn {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M4.667 7.869L11.743 4l7.59 3.932v2.02l-1.994 1.303l-5.34-3.097l-1.295.778l1.518.876v2.112l-2 1.267l-1.556-.929v1.406L14 16.68v2.077L12 20l-7.333-4.054zm.444 2.307l1.333.846v1.653l-1.333-.827zm0-2.002l1.333.79v1.666L5.11 9.846zm1.777 1.045l1.334.793v1.67l-1.334-.79zm1.778 1.057l1.333.81v1.653l-1.333-.802zM5.111 12.16l1.333.846v1.653l-1.333-.827zm0 1.972l1.333.797v1.744l-1.333-.749zm1.777 1.047l1.334.773v1.716l-1.334-.748zm1.778 1.027l1.333.78v1.683l-1.333-.755zm1.778 1.027l1.333.767v1.653l-1.333-.75zm3.111-.135l-1.333.845v1.654l1.333-.827zm-5.333-4.927l-1.334.845v1.653l1.334-.827zm3.555-1.93l-1.333.845v1.589l1.333-.827zm0-4.01l-1.333.844V8.73l1.333-.827zm.445 0l1.333.786v1.656l-1.333-.779zm1.78 1.048l1.332.788v1.655l-1.333-.796zm1.775 1.048l1.333.784v1.657l-1.333-.791zm3.114-.019l-1.334.814v1.648l1.334-.792zm-12.003 2.96v1.314l1.157-.66zM8.808 7.9L10 7.216v1.39z");
}

</style>
