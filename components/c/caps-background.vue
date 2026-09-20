<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path clip-rule="evenodd" class="n30yrnb9r"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:caps-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.n30yrnb9r {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M14.744 19.775A8.02 8.02 0 0 0 12 4.225a8.02 8.02 0 0 0-2.744 15.55h.401a1.346 1.346 0 0 0 1.34-1.374v-4.645h-1.58c-.512 0-.928-.452-.928-1.004c0-.551.416-1.003.928-1.003h5.166c.512 0 .928.452.928 1.003c0 .552-.416 1.004-.928 1.004h-1.58V18.4a1.4 1.4 0 0 0 1.405 1.374zM12 10.245a2.006 2.006 0 1 0 0-4.013a2.006 2.006 0 0 0 0 4.012m-5.518 3.51a1.003 1.003 0 1 0 0-2.006a1.003 1.003 0 0 0 0 2.007m12.039-1.003a1.003 1.003 0 1 1-2.006 0a1.003 1.003 0 0 1 2.006 0");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
