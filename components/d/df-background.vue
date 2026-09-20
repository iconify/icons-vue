<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="hw3m8wbpb"/><path class="wjp7clbfh"/><path class="l3fjlnbxx"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:df-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hw3m8wbpb {
  fill: var(--svg-color--ff9601, #ff9601);
  d: path("M24 0H0v24h24z");
}

.l3fjlnbxx {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.934 4h4.8a8 8 0 1 1 0 16H7.467v-9.6h1.6v8h2.667a6.4 6.4 0 0 0 0-12.8h-4.8z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.wjp7clbfh {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.266 7.2H11.2a4.8 4.8 0 1 1 0 9.6h-.534v-1.765h.23c1.936 0 3.504-1.408 3.504-3.12c0-1.707-1.568-3.115-3.504-3.115h-5.03v9.067h-1.6z");
}

</style>
