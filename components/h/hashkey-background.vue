<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ac68u09_e"/><path class="d22c8__jc"/><path class="iwk5w0ojg"/><path class="w-idxtb8k"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:hashkey-background" /></template>
<style>
.ac68u09_e {
  fill: var(--svg-color--0072e5, #0072e5);
  d: path("M24 0H0v24h24z");
}

.d22c8__jc {
  fill: var(--svg-color--1b2126, #1b2126);
  d: path("m8.584 4.91l-4.002-.907a.11.11 0 0 0-.132.104v15.786c0 .067.062.12.13.104l4-.824a.11.11 0 0 0 .087-.104V5.01a.1.1 0 0 0-.083-.101m6.843.001l4.002-.907a.11.11 0 0 1 .132.104v15.786c0 .067-.061.12-.13.104l-4-.824a.11.11 0 0 1-.087-.104V5.01c0-.049.034-.092.083-.101");
}

.ft5dv1b6b {
  fill: none;
}

.iwk5w0ojg {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.897 9.842h4.217l-4.217 4.215z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.w-idxtb8k {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.114 14.057H9.897l4.217-4.215z");
}

</style>
