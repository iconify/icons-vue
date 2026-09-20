<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGv6vHceQo)" class="r4i437pya"/><path clip-rule="evenodd" class="gi63xd2dt"/><path clip-rule="evenodd" class="uzq1w5b6e"/><path clip-rule="evenodd" class="jk3tazmam"/></g><defs><linearGradient id="SVGv6vHceQo" x1="5.684" x2="19.144" y1="7.922" y2="16.017" gradientUnits="userSpaceOnUse"><stop class="tq_dn5-le"/><stop offset=".42" class="v4an1_12a"/><stop offset="1" class="sfv4578gy"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:apfc-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gi63xd2dt {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("m8.108 4.217l4.108 2.265v4.55l-4.108 2.265L4 11.031V6.482zM4.432 6.958v3.818l3.46 1.911V8.67l-3.46-1.716zm3.892 1.717v4.012l3.46-1.91v-3.82zm3.213-2.076l-3.43 1.704L4.68 6.599l3.429-1.89z");
}

.jk3tazmam {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("m12 10.703l4.108 2.266v4.549L12 19.783l-4.108-2.265v-4.55zm-3.675 2.741v3.818l3.459 1.912v-4.017l-3.46-1.717zm3.891 1.717v4.013l3.46-1.912v-3.818zm3.213-2.075L12 14.789l-3.429-1.703L12 11.196z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.sfv4578gy {
  stop-color: var(--svg-color--d6b087, #d6b087);
}

.tq_dn5-le {
  stop-color: var(--svg-color--c66329, #c66329);
}

.uzq1w5b6e {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M15.892 4.217L20 6.482v4.55l-4.108 2.265l-4.108-2.266V6.482zm-3.675 2.741v3.818l3.459 1.911V8.67l-3.46-1.716zm3.891 1.717v4.012l3.46-1.91v-3.82zm3.213-2.076l-3.429 1.704l-3.429-1.704l3.43-1.89z");
}

.v4an1_12a {
  stop-color: var(--svg-color--e08d39, #e08d39);
}

</style>
