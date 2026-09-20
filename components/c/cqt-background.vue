<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="d8z5igbgc"/><path class="v_xut2bmf"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cqt-background" /></template>
<style>
.d8z5igbgc {
  fill: var(--svg-color--00d8d5, #00d8d5);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.v_xut2bmf {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.75 4a8 8 0 1 0 0 16v-3.5a4.5 4.5 0 0 1-4.5-4.5a4.5 4.5 0 0 1 4.5-4.5zm0 12.5a4.5 4.5 0 1 0 0-9m4.5.5a2 2 0 1 0 0-4a2 2 0 0 0 0 4m0 12a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

</style>
