<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ze7k3qbwt"/><path class="njandybjh"/><path class="vs5d21woj"/><path class="nnok9h56g"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ethm-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.njandybjh {
  fill: var(--svg-color--fff, #fff);
  d: path("m12 8l-5.052 2.88L12 4zm0 0l5.052 2.88L12 4zm0 1.108l-5.052 2.905L12 14.16z");
}

.nnok9h56g {
  fill: var(--svg-color--fff, #fff);
  d: path("m12 19.999l5.052-8.009L12 14.108z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vs5d21woj {
  fill: var(--svg-color--fff, #fff);
  d: path("m12 20l-5.052-8.008L12 14.11zm0-10.892l5.052 2.9L12 14.157z");
}

.ze7k3qbwt {
  fill: var(--svg-color--44a47f, #44a47f);
  d: path("M24 0H0v24h24z");
}

</style>
