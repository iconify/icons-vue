<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="gslogdcho"/><path clip-rule="evenodd" class="j15sj5-oj"/><path class="it_y3kiee"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dola-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gslogdcho {
  fill: var(--svg-color--ffbb51, #ffbb51);
  d: path("M24 0H0v24h24z");
}

.it_y3kiee {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.25 4h2.055l-5.75 16H7.5zm3 0h2.055l-5.75 16H10.5z");
}

.j15sj5-oj {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12.5 5H9.79L5 18h7.5a6.5 6.5 0 0 0 0-13m0 1.5H11l-3.75 10h5.25a5 5 0 1 0 0-10");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
