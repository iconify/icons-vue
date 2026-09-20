<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="w7f9omybi"/><path class="vcyu5d3cd"/><path class="z1-fs9mqn"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:conflux-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vcyu5d3cd {
  fill: var(--svg-color--fff, #fff);
  d: path("m15.38 13.535l-3.383 3.413l-1.883-1.9l3.384-3.413l-1.505-1.519l-4.905 4.949L11.979 20l4.906-4.949z");
}

.w7f9omybi {
  fill: var(--svg-color--37a1db, #37a1db);
  d: path("M24 0H0v24h24z");
}

.z1-fs9mqn {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.4 10.449L12.009 4l-6.41 6.467l.021 3.022l6.361-6.418l6.408 6.465z");
}

</style>
