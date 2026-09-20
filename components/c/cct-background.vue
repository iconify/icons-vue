<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="aaha48ycl"/><path class="xrcs7wbke"/><path class="n5v26hbax"/><path class="cj0m9ybhu"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cct-background" /></template>
<style>
.aaha48ycl {
  fill: var(--svg-color--4e4f4f, #4e4f4f);
  d: path("M15.223 7.356a6.7 6.7 0 0 1 1.715 3.312h-3.182a3.5 3.5 0 0 0-2.8-2.192v-1.12z");
}

.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.cj0m9ybhu {
  fill: var(--svg-color--4e504c, #4e504c);
  d: path("M7.111 12c0 1.96 1.485 3.551 3.4 3.551a3.56 3.56 0 0 0 3.267-2.217h3.111c-.609 3.035-3.235 5.333-6.378 5.333C6.911 18.667 4 15.68 4 12z");
}

.ft5dv1b6b {
  fill: none;
}

.n5v26hbax {
  fill: var(--svg-color--f0f3fa, #f0f3fa);
  d: path("M20 13.333c-.613 3.036-3.244 5.334-6.4 5.334c-3.61 0-6.49-2.987-6.49-6.667s2.88-6.667 6.489-6.667a6.58 6.58 0 0 1 6.4 5.333h-3.111a3.59 3.59 0 0 0-3.29-2.222c-1.924 0-3.377 1.596-3.377 3.556s1.454 3.55 3.378 3.55a3.59 3.59 0 0 0 3.289-2.217z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.xrcs7wbke {
  fill: var(--svg-color--4f4f4f, #4f4f4f);
  d: path("M13.147 5.902L9.316 7.857v.814A3.52 3.52 0 0 0 7.11 12H4c0-3.68 2.916-6.667 6.511-6.667a6.4 6.4 0 0 1 2.636.569");
}

</style>
