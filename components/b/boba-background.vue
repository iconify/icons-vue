<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ohn32qc7v"/><path class="az5csuy6m"/><path class="qw3ef-bnb"/><path class="smlmjgbnp"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:boba-background" /></template>
<style>
.az5csuy6m {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.044 14.666H4.748V4h7.296c2.5 0 4.53 2.03 4.53 4.535v1.595a4.534 4.534 0 0 1-4.53 4.536");
}

.ft5dv1b6b {
  fill: none;
}

.ohn32qc7v {
  fill: var(--svg-color--b0b1ac, #b0b1ac);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qw3ef-bnb {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.919 20h-9.17v-5.335a5.33 5.33 0 0 1 5.33-5.33h3.84a5.333 5.333 0 1 1 0 10.665");
}

.smlmjgbnp {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.574 10.04v.09a4.534 4.534 0 0 1-4.535 4.535h-7.29a5.33 5.33 0 0 1 5.33-5.33h3.84c.97 0 1.875.26 2.655.705");
}

</style>
