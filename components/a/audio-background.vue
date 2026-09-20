<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="lsq2bbn7k"/><path class="h5hp8bg7l"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:audio-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h5hp8bg7l {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.514 15.14c-.4 0-.645-.416-.44-.748l6.057-9.861a.526.526 0 0 1 .885 0l8.913 14.432c.2.331-.046.749-.451.749H6.988c-.4 0-.651-.423-.446-.755l1.555-2.434a.52.52 0 0 1 .44-.24h4.227a.497.497 0 0 0 .435-.76l-2.2-3.576a.504.504 0 0 0-.857 0l-1.811 2.97a.52.52 0 0 1-.44.224H4.514");
}

.lsq2bbn7k {
  fill: var(--svg-color--7e1bc6, #7e1bc6);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
