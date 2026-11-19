<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGWyRWed6Q)" class="r4i437pya"/><path class="pn6-vg7dd"/></g><defs><linearGradient id="SVGWyRWed6Q" x1="12" x2="12" y1="0" y2="24" gradientUnits="userSpaceOnUse"><stop class="l5h6e9i1g"/><stop offset="1" class="oc_pgy7yc"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lobstr-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.l5h6e9i1g {
  stop-color: var(--svg-color--35b5ce, #35b5ce);
}

.oc_pgy7yc {
  stop-color: var(--svg-color--1a96b2, #1a96b2);
}

.pn6-vg7dd {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 20c-4.024 0-6.833-2.469-6.833-6.002c0-3.345 3.82-8.847 8.133-9.998c-.978.976-2.322 2.447-3.07 4.052c-1.063 2.277-1.164 5.752-1.072 6.16l.15.66l.638-.247a7.6 7.6 0 0 0 1.974-1.14a9 9 0 0 0 1.106-1.04c1.368-1.518 2.244-3.482 2.386-5.25c1.947 1.3 3.421 4.137 3.421 6.802C18.833 17.532 16.023 20 12 20");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
