<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="m_iazhd0u"/><path class="o32zi2hhw"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:icx-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m_iazhd0u {
  fill: var(--svg-color--35b7ba, #35b7ba);
  d: path("M24 0H0v24h24z");
}

.o32zi2hhw {
  fill: var(--svg-color--fff, #fff);
  d: path("m17.263 8.03l-1.73 1.737a4.204 4.204 0 0 1-5.804 5.803l-1.738 1.731a6.619 6.619 0 0 0 9.272-9.272M7.78 12.028a4.203 4.203 0 0 1 6.378-3.607l1.745-1.745A6.617 6.617 0 0 0 6.64 15.94l1.745-1.738a4.2 4.2 0 0 1-.611-2.174zm10.727-5.12A1.456 1.456 0 1 0 18.583 4a1.456 1.456 0 0 0-.076 2.91M5.417 20a1.456 1.456 0 0 0 1.379-2.02A1.454 1.454 0 1 0 5.417 20");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
