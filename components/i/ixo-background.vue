<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="gvjr2kt8u"/><path clip-rule="evenodd" class="o03nq0bor"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ixo-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gvjr2kt8u {
  fill: var(--svg-color--00d2ff, #00d2ff);
  d: path("M24 0H0v24h24z");
}

.o03nq0bor {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M5.23 9.744a1.23 1.23 0 1 0 0-2.462a1.23 1.23 0 0 0 0 2.462m1.232.41H4v6.564h2.462zm.41 1.69v-1.69h1.62l1.662 1.65l1.64-1.65h1.642v1.645l-1.633 1.645l1.633 1.625v1.65h-1.662l-1.616-1.61l-1.596 1.61h-1.69v-1.617L8.5 13.465zM20 13.436a3.282 3.282 0 1 1-6.564 0a3.282 3.282 0 0 1 6.564 0m-2.051 0a1.23 1.23 0 1 1-2.462 0a1.23 1.23 0 0 1 2.462 0");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
