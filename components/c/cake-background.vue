<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ogxv4dbxd"/><path clip-rule="evenodd" class="bu-x4ac3o"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cake-background" /></template>
<style>
.bu-x4ac3o {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M8.95 4C7.635 4 6.75 5.2 7 6.5l.5 3c-1.97.85-3.5 2.4-3.5 4.25v1.15c0 1.55 1.01 2.85 2.425 3.7c1.46.9 3.375 1.4 5.55 1.4s4.09-.5 5.55-1.4C18.99 17.75 20 16.45 20 14.9v-1.15c0-1.85-1.53-3.35-3.5-4.2L17 6.5c.2-1.3-.735-2.5-2.05-2.5C13.79 4 13 4.95 13 6.1v2.69c-.395-.05-.725-.05-1.025-.05h-1.14L11 6.1C11 4.95 10.105 4 8.95 4m.3 11c.42 0 .75-.575.75-1.25s-.33-1.25-.75-1.25s-.75.575-.75 1.25s.33 1.25.75 1.25m5.5 0c.42 0 .75-.575.75-1.25s-.33-1.25-.75-1.25s-.75.575-.75 1.25s.33 1.25.75 1.25");
}

.ft5dv1b6b {
  fill: none;
}

.ogxv4dbxd {
  fill: var(--svg-color--522d0b, #522d0b);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
