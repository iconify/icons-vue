<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="vfa7f2b6k"/><path class="osth9kkbv"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:fx-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.osth9kkbv {
  fill: var(--svg-color--fff, #fff);
  d: path("M6 11H4v-1h2c0 .024 0-.03 0 0c0-.33-.02-.83 0-1.16c.04-.626 0-1.2.355-1.716a2.5 2.5 0 0 1 1.51-1.01c.5-.125 1-.135 1.51-.09c.525.05 1.046.17 1.536.37l.09.04l-.34.89l-.205-.085a3.76 3.76 0 0 0-2.01-.21C7.665 7.16 7 7.74 7 8.63V10h3v1H7v7H6zm10.25 3.498l1.25-2.5h-1l-1 2l-1-2h-1l1.25 2.5l-1.25 2.5h1l1-2l1 2h1zm-3.23 2.96l-.625.54c-1.76-1.715-1.95-5.005-.01-7l.63.55c-.8.97-1.015 1.685-1.015 2.95c0 .975.405 2.22 1.02 2.96m4.96 0l.63.54c1.75-1.715 1.95-5.005.006-7l-.63.55c.8.97 1.015 1.665 1.015 2.95c0 1.025-.41 2.206-1.02 2.96");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vfa7f2b6k {
  fill: var(--svg-color--f7d509, #f7d509);
  d: path("M24 0H0v24h24z");
}

</style>
