<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="kron8_04t"/><path class="li2v-kbmt"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gho-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kron8_04t {
  fill: var(--svg-color--c9b4f9, #c9b4f9);
  d: path("M24 0H0v24h24z");
}

.li2v-kbmt {
  fill: var(--svg-color--000, #000);
  d: path("M14.421 12h3.1L20 16.267v2.666h-9.456C6.928 18.933 4 15.941 4 12.245v-.49c0-3.702 2.933-6.689 6.544-6.689h3.973l1.536 2.667h-5.189a4.213 4.213 0 0 0-4.16 4.256c0 2.347 1.861 4.278 4.16 4.278h6.037zm-2.954-1.867a1.334 1.334 0 1 1-2.668 0a1.334 1.334 0 0 1 2.668 0m0 3.733a1.334 1.334 0 1 1-2.668 0a1.334 1.334 0 0 1 2.668 0");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
