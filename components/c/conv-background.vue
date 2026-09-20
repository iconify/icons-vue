<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="zqswphd1e"/><path class="h51m9m1ga"/><path class="ar7fwbbmx"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:conv-background" /></template>
<style>
.ar7fwbbmx {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.698 6.385L15.804 8.26a5.333 5.333 0 1 0 0 7.48l1.889 1.88a8 8 0 1 1 .005-11.235");
}

.ft5dv1b6b {
  fill: none;
}

.h51m9m1ga {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.853 7.875L14.69 12l4.16 4.133A7.95 7.95 0 0 0 20 12c0-1.511-.418-2.92-1.147-4.125");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.zqswphd1e {
  fill: var(--svg-color--e31c38, #e31c38);
  d: path("M24 0H0v24h24z");
}

</style>
