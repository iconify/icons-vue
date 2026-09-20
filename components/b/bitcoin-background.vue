<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="dgzsbjbvn"/><path class="dna2qhxmx"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bitcoin-background" /></template>
<style>
.dgzsbjbvn {
  fill: var(--svg-color--f7931a, #f7931a);
  d: path("M24 0H0v24h24z");
}

.dna2qhxmx {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.011 10.432c.249-1.684-1.026-2.582-2.783-3.192l.57-2.27l-1.388-.345l-.553 2.214l-1.107-.265l.561-2.23L11.924 4l-.57 2.278l-.881-.209v-.008L8.556 5.58l-.37 1.483s1.027.242 1.01.25c.563.144.659.513.643.801l-.642 2.599l.145.048l-.153-.032l-.906 3.633c-.064.169-.241.425-.633.32c.015.024-1.003-.24-1.003-.24l-.69 1.58l1.805.449l.986.257l-.577 2.302l1.387.344l.562-2.277l1.114.288l-.569 2.27l1.387.345l.57-2.302c2.365.449 4.146.273 4.892-1.869c.602-1.724-.032-2.71-1.275-3.368c.906-.2 1.588-.802 1.764-2.03zm-3.168 4.443c-.425 1.725-3.328.786-4.266.561l.762-3.055c.938.24 3.954.698 3.504 2.486zm.425-4.467c-.385 1.564-2.807.77-3.585.578l.69-2.768c.786.193 3.304.562 2.896 2.19");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
