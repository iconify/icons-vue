<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="kglq3sbta"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ledger-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kglq3sbta {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 15.111v4.09h6.018v-.908H4.877v-3.182zm15.123 0v3.182h-5.141v.907H20v-4.09zM10.027 8.89v6.222h3.955v-.818h-3.078V8.89zM4 4.8v4.09h.877V5.707h5.141V4.8zm9.982 0v.907h5.141v3.182H20V4.8z");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
