<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="c8b1vubah"/><path class="q1bs8obxx"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dot-background" /></template>
<style>
.c8b1vubah {
  fill: var(--svg-color--e6007a, #e6007a);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q1bs8obxx {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.82 5.647c0 .908-1.266 1.647-2.824 1.647s-2.824-.739-2.824-1.647S10.443 4 11.996 4s2.823.739 2.823 1.647m0 12.706c0 .908-1.266 1.647-2.824 1.647s-2.824-.739-2.824-1.647s1.271-1.647 2.824-1.647s2.823.739 2.823 1.647M7.925 9.718c.8-1.38.805-2.87.02-3.323c-.791-.456-2.071.297-2.871 1.676c-.8 1.378-.8 2.87-.02 3.322c.791.452 2.071-.296 2.871-1.675m11.003 2.884c.79.447.786 1.91-.01 3.266c-.8 1.356-2.084 2.09-2.87 1.643c-.796-.447-.79-1.911.005-3.266c.8-1.356 2.084-2.09 2.875-1.643M7.948 17.52c.792-.447.787-1.91-.013-3.266c-.795-1.355-2.08-2.09-2.87-1.642c-.796.451-.791 1.91.009 3.266c.795 1.355 2.08 2.094 2.87 1.647zm10.98-9.445c.8 1.38.8 2.866.014 3.318c-.786.456-2.07-.292-2.87-1.675c-.791-1.38-.8-2.866-.015-3.318c.79-.456 2.07.292 2.87 1.675");
}

</style>
