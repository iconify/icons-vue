<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="xr7cvgsvh"/><path class="cgs6972xh"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:layer-background" /></template>
<style>
.cgs6972xh {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 4.571h16V8H4zm0 5.715h16v3.429H4zM4 16h16v3.429H4z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.xr7cvgsvh {
  fill: var(--svg-color--ff47a2, #ff47a2);
  d: path("M24 0H0v24h24z");
}

</style>
