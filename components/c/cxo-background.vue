<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="s0kd6pp3q"/><path class="ssawi__bn"/><path class="q9ywivk1k"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cxo-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q9ywivk1k {
  fill: var(--svg-color--fff, #fff);
  d: path("M17 17.75v-1.5h-1.5v1.5H14v-1.5h1.5v-3H14v-1.5h-1.5v-1.5H14v-1.5h-1.5v-1.5H14v1.5h1.5v-2.5H17v-1.5h-4l-2.25 4l-2.525-4H4L8.5 12L4 19.25h4.136l2.614-4.5l2.25 4.5h5.5v-1.5zm-4.5-3v-1.5H11v-1.5l-1.5.005V10.25H11v1.5h1.5v1.5H14v1.5z");
}

.s0kd6pp3q {
  fill: var(--svg-color--8ddb2e, #8ddb2e);
  d: path("M24 0H0v24h24z");
}

.ssawi__bn {
  fill: var(--svg-color--fff, #fff);
  d: path("M20 4.75h-1.5v1.5H20zm-1.5 1.5h-1.502v1.5H18.5zm1.5 9.5h-1.5v1.5H20zm-1.5-2.5H17v1.5h1.5zm-3-3H14v1.5h1.5zm1.5-1.5h-1.5v1.5H17zm3 1.5h-1.5v1.5H20z");
}

</style>
