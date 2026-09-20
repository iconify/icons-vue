<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="hfmn0jbtl"/><path class="zvb5nua0t"/><path class="c1ui5hbdr"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:emaid-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.c1ui5hbdr {
  fill: var(--svg-color--2a5789, #2a5789);
  d: path("m12.267 11.76l-2.134-1.333l8.8-5.307v12.192c0 .523-.256 1.013-.683 1.307l-1.983 1.38V9.372z");
}

.ft5dv1b6b {
  fill: none;
}

.hfmn0jbtl {
  fill: var(--svg-color--99bce3, #99bce3);
  d: path("m16.267 9.37l-2.134 1.211v4.901l-9.066-5.317v2.283c0 .565.299 1.082.784 1.37L16.267 20z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.zvb5nua0t {
  fill: var(--svg-color--5892cd, #5892cd);
  d: path("M14.133 15.483v-2.661l-4-2.39l8.8-5.317l-1.898-.944a1.6 1.6 0 0 0-1.51.037L5.067 10.166z");
}

</style>
