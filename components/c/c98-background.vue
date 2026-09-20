<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="s1ig8jbyp"/><path clip-rule="evenodd" class="obptbbbuv"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:c98-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.obptbbbuv {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 9.75a4 4 0 1 1-8 0a4 4 0 0 1 8 0m-1.5 0a2.5 2.5 0 1 1-5.002 0a2.5 2.5 0 0 1 5.002 0m-4.5 5H4.5a3.5 3.5 0 0 0 7 0H10a2 2 0 0 1-4 0m3-5a1 1 0 1 1-1.25-.97v-.53h.5v.53a1 1 0 0 1 .75.97m7 .5a4 4 0 1 1 0 8a4 4 0 0 1 0-8m0 1.5a2.5 2.5 0 1 1 0 5a2.5 2.5 0 0 1 0-5m1 2.5a1 1 0 1 0-1.25.97v.53h.5v-.53a1 1 0 0 0 .75-.97m-1-8.5a3.5 3.5 0 0 1 3.165 4.99a4.7 4.7 0 0 0-1.28-.825a2 2 0 1 0-3.77 0a4.6 4.6 0 0 0-1.28.825A3.498 3.498 0 0 1 16 5.75");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.s1ig8jbyp {
  fill: var(--svg-color--0a0000, #0a0000);
  d: path("M24 0H0v24h24z");
}

</style>
