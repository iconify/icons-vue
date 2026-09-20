<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="eejn39bcp"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gcoin-background" /></template>
<style>
.eejn39bcp {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.486 8.082v4.878l-4.572 4.489v1.66L12 20l-.937-.914v-1.66L6.514 12.96V5.829h4.572V4h1.828v1.829H16.6l-2.2 2.285H8.8v3.955l2.286 2.331V9.943h1.828v4.452l2.286-2.331v-1.829z");
}

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

</style>
