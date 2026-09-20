<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="t0_m_sqsa"/><path class="g7s8cacun"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dc-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g7s8cacun {
  fill: var(--svg-color--fff, #fff);
  d: path("m14.916 14.396l-1.92-2.376v-4.6l2.056 3.488L16.4 9.896l1.244 2.316zm2.82-2.016L20 16.6H4l3.424-4.896l3.312 3.068l2.16-2.572l1.988 2.464l2.852-2.28zm-10.2-.836L10.72 14.5l2.08-2.484V7.4l-1.916 2.752l-1.308-1.528z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.t0_m_sqsa {
  fill: var(--svg-color--f30, #f30);
  d: path("M24 0H0v24h24z");
}

</style>
