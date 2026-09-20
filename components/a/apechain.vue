<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGdTsR8dtt)"><path class="xg8_nc1ux"/><path class="xnjpnybdp"/></g><defs><clipPath id="SVGdTsR8dtt"><path class="g1t4b6brm"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:apechain" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g1t4b6brm {
  fill: var(--svg-color--fff, #fff);
  d: path("M3 5h18v13.761H3z");
}

.xg8_nc1ux {
  stroke: var(--svg-color--0054fa, #0054fa);
  stroke-width: var(--svg-stroke-width--2-256px, 2.256px);
  d: path("M20.784 5.027H3.22a.16.16 0 0 0-.161.161v13.395c0 .09.072.161.161.161h17.564a.16.16 0 0 0 .161-.16V5.187a.16.16 0 0 0-.16-.16Z");
}

.xnjpnybdp {
  fill: var(--svg-color--0054fa, #0054fa);
  d: path("M7.191 8.18h1.424l.917 7.632H8.326l-.134-1.66h-.64l-.134 1.66H6.274zm.568 3.394l-.124 1.567h.474l-.134-1.567l-.093-1.32h-.03zm4.302 4.238h-1.227V8.181h1.609c.877 0 1.413.515 1.413 1.444v1.877c0 .917-.536 1.433-1.413 1.433h-.382zm.01-3.795h.269c.206 0 .289-.185.289-.515V9.625c0-.34-.083-.526-.29-.526h-.267zm3.199 3.795V8.181h2.392v1.01h-1.165v2.259h1.041v1.01h-1.041v2.342h1.165v1.01z");
}

</style>
