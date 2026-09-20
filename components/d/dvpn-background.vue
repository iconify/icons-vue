<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="m7uycdddf"/><path clip-rule="evenodd" class="bbb6e170n"/><path class="q5esctcsr"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dvpn-background" /></template>
<style>
.bbb6e170n {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M19.512 4H4.488v7.753C4.488 15.8 7.852 20 12 20s7.512-4.201 7.512-8.247zm-.537.488H5.025v7.276c0 3.81 3.123 7.748 6.975 7.748s6.975-3.944 6.975-7.748z");
}

.ft5dv1b6b {
  fill: none;
}

.m7uycdddf {
  fill: var(--svg-color--07b3f5, #07b3f5);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q5esctcsr {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.365 6.097H6.635v2.988l8.429 5.833l-.601.51l-7.829-5.275v1.664c0 2.988 2.404 6.084 5.366 6.084c2.94 0 5.328-3.047 5.365-6.015L9.998 6.848h1.417l5.95 4.137z");
}

</style>
