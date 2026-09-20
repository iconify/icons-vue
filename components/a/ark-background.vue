<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="k-dm1f34s"/><path class="p4xlkac8c"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ark-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k-dm1f34s {
  fill: var(--svg-color--f70000, #f70000);
  d: path("M24 0H0v24h24z");
}

.p4xlkac8c {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.963 10.048L4 18.548l8-13.176l8 13.257zm1.15 3.324h-2.487L11.906 12l1.214 1.372zm-4.8 2.285l1.418-1.371h4.306l1.454 1.371z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
