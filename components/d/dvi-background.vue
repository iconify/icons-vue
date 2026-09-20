<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path clip-rule="evenodd" class="v7sjrobhl"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dvi-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.v7sjrobhl {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M5.217 4.126A.17.17 0 0 1 5.387 4h4.402l8.912 5.178a.18.18 0 0 1 .082.194h.005l-.01.015a.2.2 0 0 1-.038.058L12.015 20H7.404L5.227 4.243a.17.17 0 0 1-.01-.097l-.005-.02zm2.56.218l.131.955l1.944 1.145l-.29-2.1zm1.697 12.49L7.966 5.73l1.95 1.144l1.066 7.612l-1.503 2.347zm.073.524l.29 2.123l1.514-2.376l-.296-2.094l-1.503 2.347zm1.794-2.793l.29 2.09l4.51-7.099h-1.586zm3.224-5.353l-.024-.014l-4.315-2.536l-.306-2.187l8.155 4.737zm-.33.204l-2.972 4.63l-.97-6.948z");
}

</style>
