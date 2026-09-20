<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="pa_bm_ehr"/><path class="ke_na8b5o"/><path clip-rule="evenodd" class="ii7kgtbjy"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:clover-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ii7kgtbjy {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M7.84 4h8.32A3.84 3.84 0 0 1 20 7.84v8.32A3.84 3.84 0 0 1 16.16 20H7.84A3.84 3.84 0 0 1 4 16.16V7.84A3.84 3.84 0 0 1 7.84 4m9.28 8a5.12 5.12 0 1 1-10.24 0a5.12 5.12 0 0 1 10.24 0");
}

.ke_na8b5o {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.362 9.29a.267.267 0 0 0-.266.266v1.56h-1.54a.267.267 0 0 0-.267.266v1.293c0 .147.12.266.266.266h1.54v1.503c0 .147.12.266.267.266h1.274a.266.266 0 0 0 .267-.266v-1.56h-1.807v-1.769h1.807v1.826h1.54a.266.266 0 0 0 .267-.266v-1.293a.267.267 0 0 0-.266-.267h-1.541v-1.56a.267.267 0 0 0-.267-.266z");
}

.pa_bm_ehr {
  fill: var(--svg-color--0c0b0b, #0c0b0b);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
