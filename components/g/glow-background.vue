<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGEu8wweXm)" class="r4i437pya"/><path class="qmq3lvwgk"/></g><defs><linearGradient id="SVGEu8wweXm" x1=".012" x2="23.98" y1="-.048" y2="24.011" gradientUnits="userSpaceOnUse"><stop class="qaja-xbzz"/><stop offset="1" class="xnf3oubdt"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:glow-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qaja-xbzz {
  stop-color: var(--svg-color--6f03fb, #6f03fb);
}

.qmq3lvwgk {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.61 17.703A7.98 7.98 0 0 1 12 20a7.97 7.97 0 0 1-5.6-2.288a9.095 9.095 0 0 1 11.21-.01m.093-.092A7.98 7.98 0 0 0 20 12c0-2.18-.872-4.156-2.286-5.6c-2.582 3.286-2.585 7.932-.011 11.21m-.08-11.302a9.095 9.095 0 0 1-11.236-.01A7.97 7.97 0 0 1 12 4a7.98 7.98 0 0 1 5.623 2.309m-11.324.078A7.97 7.97 0 0 0 4 12c0 2.192.882 4.178 2.309 5.623a9.095 9.095 0 0 0-.01-11.236");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.xnf3oubdt {
  stop-color: var(--svg-color--ec5eff, #ec5eff);
}

</style>
