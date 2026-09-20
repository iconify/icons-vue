<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mga1-jbuu"/><path class="j4sqmx0go"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:litecoin-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.j4sqmx0go {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.43 15.21L5 15.77L5.69 13l1.44-.58L9.21 4h5.13l-1.52 6.2l1.41-.57l-.68 2.74l-1.42.58l-.85 3.621H19L18.13 20H5.25z");
}

.mga1-jbuu {
  fill: var(--svg-color--345d9d, #345d9d);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
