<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="rl8syevpz"/><path class="xscz-ooib"/><path class="lq9ycccjp"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:block-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lq9ycccjp {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.036 8.362L6.826 12l2.195 3.609l-1.402 2.342L4 12l3.65-6.01z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rl8syevpz {
  fill: var(--svg-color--2d338a, #2d338a);
  d: path("M24 0H0v24h24z");
}

.xscz-ooib {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.205 5.412H16L20 12l-4 6.588H8.137L12.069 12zm4.137 2.353L14.895 12l-2.552 4.235h2.286L17.166 12l-2.553-4.235h-2.278z");
}

</style>
