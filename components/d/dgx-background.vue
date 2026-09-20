<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="y71nzlbjy"/><path class="ua9sgob8y"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dgx-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.ua9sgob8y {
  fill: var(--svg-color--fff, #fff);
  d: path("m12 11l4.5 4.5L12 20zm0 0v9l-4.5-4.5zm0-7v5.865L6.91 15L4 12.065zm0 0l8 8.065L17.09 15L12 9.865z");
}

.y71nzlbjy {
  fill: var(--svg-color--243961, #243961);
  d: path("M24 0H0v24h24z");
}

</style>
