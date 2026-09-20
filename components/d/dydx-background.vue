<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGPtH3ibLE)" class="r4i437pya"/><path class="b9pg8rbzd"/></g><defs><linearGradient id="SVGPtH3ibLE" x1="15.039" x2="-2.44" y1="20.231" y2="-5.463" gradientUnits="userSpaceOnUse"><stop class="fk3a3gb7j"/><stop offset="1" class="da6k7acbo"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dydx-background" /></template>
<style>
.b9pg8rbzd {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.685 4L4.571 20h3.412l11.17-16zM8.343 4l3.268 4.714l-1.708 2.572L4.857 4zm7.674 16l-3.628-5.217l1.708-2.497L19.43 20z");
}

.da6k7acbo {
  stop-color: var(--svg-color--6966ff, #6966ff);
  stop-opacity: 0.36;
}

.fk3a3gb7j {
  stop-color: var(--svg-color--6966ff, #6966ff);
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

</style>
