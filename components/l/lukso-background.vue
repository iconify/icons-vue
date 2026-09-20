<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="d1zdbabvi"/><path clip-rule="evenodd" class="g-pbsiz0g"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lukso-background" /></template>
<style>
.d1zdbabvi {
  fill: var(--svg-color--fe005b, #fe005b);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.g-pbsiz0g {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("m13.311 4.356l4.577 2.672A2.66 2.66 0 0 1 19.2 9.326v5.346c0 .947-.501 1.822-1.312 2.297l-4.577 2.675a2.59 2.59 0 0 1-2.623 0l-4.577-2.675A2.66 2.66 0 0 1 4.8 14.672V9.326c0-.948.5-1.823 1.311-2.298l4.577-2.672a2.59 2.59 0 0 1 2.623 0m.96 10.56l1.362-2.385a1.07 1.07 0 0 0-.006-1.062l-1.36-2.385a1.04 1.04 0 0 0-.909-.53h-2.722c-.375 0-.721.201-.908.53L8.367 11.47a1.08 1.08 0 0 0 0 1.062l1.364 2.385a1.05 1.05 0 0 0 .908.53h2.725l.07-.002a1.04 1.04 0 0 0 .837-.528");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
