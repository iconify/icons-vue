<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG4KxsIcBx)" class="r4i437pya"/><path class="aiy2w5bth"/></g><defs><linearGradient id="SVG4KxsIcBx" x1="7.161" x2="19.06" y1="16.857" y2="10.391" gradientUnits="userSpaceOnUse"><stop class="zzyp99m5y"/><stop offset="1" class="sgdfn7bki"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dcb-background" /></template>
<style>
.aiy2w5bth {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.323 6.58c0-2.203 1.249-2.58 2.58-2.58v10.359c0 1.156.052 2.168-.516 3.06c1.032 0 2.064 1.188 2.064 2.581h-7.483c-2.978 0-5.42-2.529-5.42-5.641c0-3.118 2.633-5.714 5.61-5.714c1.105 0 2.313.439 3.165 1.032zm-3.164 10.84c1.651 0 3.163-1.343 3.163-3.061a3.195 3.195 0 0 0-3.132-3.133a3.097 3.097 0 0 0-3.061 3.097c0 1.724 1.383 3.096 3.03 3.096");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.sgdfn7bki {
  stop-color: var(--svg-color--4d0e75, #4d0e75);
}

.zzyp99m5y {
  stop-color: var(--svg-color--c41859, #c41859);
}

</style>
