<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="hdrawlbap"/><path class="d97v1_u5f"/><path class="v_p59jhzt"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:crowd-background" /></template>
<style>
.d97v1_u5f {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.29 13.11c-.452-.137-.933.18-1.273.512c-.568.552-1.573.78-2.426.78a2.402 2.402 0 1 1 2.122-3.522a2 2 0 0 1 .84-.929a3.598 3.598 0 1 0-2.962 5.652c1.717 0 3.643-.792 4.003-2.401zm1.545-.03l.36.12l.325.064a1.12 1.12 0 0 0-.68-.184zm1.185.584c-.232.184-.668.32-1.28.332c.712 1.073 2.253 1.606 3.658 1.606a3.604 3.604 0 0 0 2.547-6.15a3.6 3.6 0 0 0-2.547-1.055c-1.23 0-2.754 1.06-3.403 2.001c-.2.6.2 1 .4 1.201c.4-.76 2.082-2.001 3.003-2.001a2.402 2.402 0 1 1 0 4.803c-.829 0-1.802-.216-2.378-.737");
}

.ft5dv1b6b {
  fill: none;
}

.hdrawlbap {
  fill: var(--svg-color--0b9ed9, #0b9ed9);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.v_p59jhzt {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.793 12.001a.8.8 0 1 0 0-1.6a.8.8 0 0 0 0 1.6m2.402 1.6a.8.8 0 1 0 0-1.601a.8.8 0 0 0 0 1.601");
}

</style>
