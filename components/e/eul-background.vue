<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="un29m_bku"/><path class="na8uhy0uf"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:eul-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.na8uhy0uf {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.4 10.098a1.595 1.595 0 0 1 .73-2.106l7.91-3.84a1.53 1.53 0 0 1 2.061.75a1.595 1.595 0 0 1-.73 2.1L6.46 10.848a1.53 1.53 0 0 1-2.06-.75m.505 5.441a1.715 1.715 0 0 1 .76-2.236l5.301-2.64c.8-.4 1.75-.045 2.13.795a1.715 1.715 0 0 1-.76 2.235l-5.3 2.64c-.8.4-1.75.046-2.13-.794M8.9 19.098a1.595 1.595 0 0 1 .73-2.105l7.912-3.84a1.53 1.53 0 0 1 2.06.75a1.595 1.595 0 0 1-.73 2.1l-7.911 3.845a1.53 1.53 0 0 1-1.706-.257q-.226-.212-.354-.493");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.un29m_bku {
  fill: var(--svg-color--37bec1, #37bec1);
  d: path("M24 0H0v24h24z");
}

</style>
