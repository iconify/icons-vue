<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGIr1GOqBF)" class="r4i437pya"/><path class="q3mgwvb8f"/></g><defs><linearGradient id="SVGIr1GOqBF" x1="12" x2="12" y1="3.999" y2="20" gradientUnits="userSpaceOnUse"><stop offset=".32" class="txd956w6a"/><stop offset="1" class="ihzvlub3d"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dfx-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ihzvlub3d {
  stop-color: var(--svg-color--3f28f7, #3f28f7);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q3mgwvb8f {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 4.005v8.03l-3.145-3.2c-1.015.87-1.325 2.515-1.37 3.2c0 2.725 2.72 4.625 4.515 4.43V20c-6.31-.3-7.965-5.435-8-7.965c0-5.62 4.845-8.16 8-8.03m0 15.99v-8.03l3.145 3.2c1.015-.87 1.325-2.515 1.37-3.2c0-2.725-2.72-4.625-4.515-4.43V4c6.31.3 7.965 5.435 8 7.965c0 5.62-4.845 8.16-8 8.03");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.txd956w6a {
  stop-color: var(--svg-color--00e8f2, #00e8f2);
}

</style>
