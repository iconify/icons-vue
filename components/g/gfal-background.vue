<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="plr014dti"/><path class="oefbi41qm"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gfal-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.oefbi41qm {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.941 16V8L12 4l3.59 2l-7.355 4.25v4.249L12 16.235l3.765-1.882v-4.254L19.059 8v8L12 20z");
}

.plr014dti {
  fill: var(--svg-color--f113a3, #f113a3);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
