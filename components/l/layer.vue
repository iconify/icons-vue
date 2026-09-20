<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="p9c-20bqp"/><path class="tkpm1_sxr"/><path class="emcz3ebwo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:layer" /></template>
<style>
.emcz3ebwo {
  fill: var(--svg-color--fff, #fff);
  d: path("M3 16.5h18v3.857H3z");
}

.ft5dv1b6b {
  fill: none;
}

.p9c-20bqp {
  fill: var(--svg-color--fff, #fff);
  d: path("M3 3.643h18V7.5H3z");
}

.tkpm1_sxr {
  fill: var(--svg-color--ff47a2, #ff47a2);
  d: path("M3 10.071h18v3.858H3z");
}

</style>
