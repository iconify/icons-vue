<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGrypylcIE)" class="r4i437pya"/><path class="yaeytd29q"/></g><defs><linearGradient id="SVGrypylcIE" x1="12.578" x2="7" y1="6.102" y2="19.404" gradientUnits="userSpaceOnUse"><stop class="u315cdrqy"/><stop offset="1" class="hrq8_nbkj"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gmx-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hrq8_nbkj {
  stop-color: var(--svg-color--4e09f8, #4e09f8);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.u315cdrqy {
  stop-color: var(--svg-color--03d1cf, #03d1cf);
  stop-opacity: 0.99;
}

.yaeytd29q {
  fill: var(--svg-color--fff, #fff);
  d: path("M20 18.222L12.013 5.778L4 18.222h11.165l-3.156-4.75L10.453 16H8.787l3.226-5.022l4.663 7.244z");
}

</style>
