<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="s3qz3ubhm"/><path class="l3hc-zkhb"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dht-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.l3hc-zkhb {
  fill: var(--svg-color--fff, #fff);
  d: path("m13.39 4.005l-2.78 1.107v12.84l2.78-1.113V4zm-5.098 7.833l-2.78 1.121V20l2.78-1.117zM18.49 9.975l-2.78-1.099v8.482l2.78 1.122z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.s3qz3ubhm {
  fill: var(--svg-color--00a0d0, #00a0d0);
  d: path("M24 0H0v24h24z");
}

</style>
