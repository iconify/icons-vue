<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="hcf6omv-d"/><path class="ah7an6bdv"/><path class="yragslhys"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lcc-background" /></template>
<style>
.ah7an6bdv {
  fill: var(--svg-color--068210, #068210);
  d: path("M10.11 8.57L8.765 4.645l3.84.755l1.215 3.81l-2.535 2.794l-3.825-.65zm5.525 4.92l-1.35-3.93l3.845.76l1.21 3.81l-2.535 2.794l-3.82-.65zM8.58 15.924L7.235 12l3.84.76l1.215 3.81l-2.535 2.79l-3.825-.65z");
}

.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.hcf6omv-d {
  fill: var(--svg-color--2ab643, #2ab643);
  d: path("M5.53 7.475L8.53 4l4.54.955l1.395 4.035l4.14.875L20 14.19l-2.925 3.475l-4.325-.825L9.985 20l-4.455-.85L4 14.72l2.85-3.29l-1.32-3.95z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.yragslhys {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.786 12.565L7.08 7.415L9.556 5.78l1.465 4.19l1.22-1.47l.465 1.225l-1.28 1.55l.815 2.21l4.18-2.615l.67 1.8l-6.8 4.23l-1.1-3l-1.175 1.385L7.566 14z");
}

</style>
