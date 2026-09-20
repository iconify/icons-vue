<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGWPc4FbhL)" class="r4i437pya"/><path class="vymapfbbt"/></g><defs><linearGradient id="SVGWPc4FbhL" x1="21.066" x2="21.066" y1="-1.814" y2="20" gradientUnits="userSpaceOnUse"><stop class="lp62i_bph"/><stop offset="1" class="ms--htbps"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:blox-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lp62i_bph {
  stop-color: var(--svg-color--84f9c8, #84f9c8);
}

.ms--htbps {
  stop-color: var(--svg-color--7fb7f6, #7fb7f6);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.vymapfbbt {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.5 11.465L4 8.265v8L11.5 20zM12 4L4.535 7.2L12 10.4l7.464-3.2zm8 4l-7.5 3.465v8.534l7.5-3.734z");
}

</style>
