<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="jss1cbcnz"/><path clip-rule="evenodd" class="vtjp1nlcj"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:flux-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jss1cbcnz {
  fill: var(--svg-color--2c61d3, #2c61d3);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vtjp1nlcj {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M19.059 8L12 4L4.941 8v3.692l2.353-1.332l2.353 1.332v-1.026l5.412-3.11l4 2.299zm0 8l-4.155 2.354l-3.845-2.243v-4.666l4-2.333l4 2.333zm-5.519 3.127L12 20l-3.333-1.889l1.565-.886zm-6.168-1.75l2.275-1.327v-2.744l-2.353-1.372l-2.353 1.372V16z");
}

</style>
