<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="fz9cc8bsx"/><path class="tvtajn7_n"/><path class="tszmyw44k"/><path class="f_a1w83ye"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:frm-background" /></template>
<style>
.f_a1w83ye {
  fill: var(--svg-color--fff, #fff);
  d: path("m18.117 7.67l.706.452v7.633L11.67 20l-1.412-.95l7.153-4.245V8.14l.706-.475z");
}

.ft5dv1b6b {
  fill: none;
}

.fz9cc8bsx {
  fill: var(--svg-color--cca362, #cca362);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.tszmyw44k {
  fill: var(--svg-color--fff, #fff);
  d: path("m16 8.62l-8 4.518v2.14l8-4.752zm-7.059 9.512l-1.412-.95L16 11.953v1.906l-7.058 4.283z");
}

.tvtajn7_n {
  fill: var(--svg-color--fff, #fff);
  d: path("m5.177 15.77l.706.409l.706-.414v-3.06l10.532-5.858l-1.412-.95l-9.12 4.908V8.828l7.708-3.877L12.885 4L5.178 7.906z");
}

</style>
