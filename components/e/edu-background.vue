<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="cgfs0jbfj"/><path class="deant62kw"/><path class="aj8mhe-bs"/><path class="b47pw0bmc"/><path class="smmk8pb9q"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:edu-background" /></template>
<style>
.aj8mhe-bs {
  fill: var(--svg-color--fff, #fff);
  d: path("m9 14.225l-4.5-2.502v1.664l4.5 2.46zm-4.5-4.34l6.502 3.47l1.461-.95s-.161-.173-.35-.29L4.678 8.093a.54.54 0 0 0-.177.38z");
}

.b47pw0bmc {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.413 4.143L4.676 8.094l1.436.834l2.353-1.306l6.045 3.467l1.353-.935a1.5 1.5 0 0 0-.433-.387l-5.371-3.02l2.012-1.11l5.926 3.413l1.384-.92c-.098-.206-.335-.358-.457-.433l-6.29-3.554c-.532-.253-1.014-.116-1.22 0");
}

.cgfs0jbfj {
  fill: var(--svg-color--4273eb, #4273eb);
  d: path("M24 0H0v24h24z");
}

.deant62kw {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.5 16.047v-1.136l6.5 3.336v-4.891l1.46-.96a.8.8 0 0 1 .04.278v6.39c0 1.064-1.13 1.057-1.62.775c-1.63-.935-5.48-2.848-5.85-3.014c-.37-.167-.524-.588-.53-.778");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.smmk8pb9q {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.5 19.653v-8.557l1.36-.943c.111.12.14.32.14.393v8.138zm3.5-2.144V9.054l1.36-.93c.111.118.14.315.14.387v7.644s0 .32-.226.482z");
}

</style>
