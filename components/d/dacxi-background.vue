<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG7MI9DbML)" class="r4i437pya"/><path class="cy0zsxqji"/></g><defs><linearGradient id="SVG7MI9DbML" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="ryzkgibxi"/><stop offset=".78" class="ushekxd_n"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dacxi-background" /></template>
<style>
.cy0zsxqji {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.334 5.537c0-.329.177-.631.466-.8l1.013-.596a1.03 1.03 0 0 1 1.04 0l1.014.596a.93.93 0 0 1 .467.8V16.17c0 .675-.365 1.293-.956 1.63l-.338.192l-3.818-2.2l.952-.56a.33.33 0 0 0 .16-.284V5.533zm-.89 2.96a1.93 1.93 0 0 0-1.4.2l-3.422 1.947a1.88 1.88 0 0 0-.955 1.631v.307l3.555 2.053v-1.138c0-.12.063-.222.16-.284l1.236-.724a.32.32 0 0 1 .32 0l.507.297zM6.667 13.61v2.56c0 .675.365 1.293.956 1.63l3.422 1.948c.592.337 1.32.337 1.912 0l2.187-1.245z");
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

.ryzkgibxi {
  stop-color: var(--svg-color--0584be, #0584be);
}

.ushekxd_n {
  stop-color: var(--svg-color--244e78, #244e78);
}

</style>
