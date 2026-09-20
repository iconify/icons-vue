<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="j8l4qlb6c"/><path class="iolp_4bre"/><path class="o3cpoojuh"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ixt-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.iolp_4bre {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 7.556h2.222v2.222H4zm0 3.11h2.222v5.779H4zm12.22-3.11H20l-4.51 4.425L20 16.445h-3.78l-4.664-4.464z");
}

.j8l4qlb6c {
  fill: var(--svg-color--245771, #245771);
  d: path("M24 0H0v24h24z");
}

.o3cpoojuh {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.892 7.556H7.11l4.51 4.425l-4.51 4.464h3.78l4.664-4.464z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
