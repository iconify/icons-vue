<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="rj7i_vbvy"/><path class="l2hm17bbb"/><path class="l6ktxey1k"/><path class="n-1_6qkmh"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:clv-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.l2hm17bbb {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 8a4 4 0 1 0-8 0a4 4 0 0 0 8 0");
}

.l6ktxey1k {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 16a4 4 0 1 0-8 0a4 4 0 0 0 8 0m8-8a4 4 0 1 0-8 0a4 4 0 0 0 8 0");
}

.n-1_6qkmh {
  fill: var(--svg-color--fff, #fff);
  d: path("M20 16a4 4 0 1 0-8 0a4 4 0 0 0 8 0");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rj7i_vbvy {
  fill: var(--svg-color--50c07c, #50c07c);
  d: path("M24 0H0v24h24z");
}

</style>
