<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="w0eobxbtu"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:intr-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.w0eobxbtu {
  fill: var(--svg-color--fff, #fff);
  d: path("m8.464 8.001l10.346-.02l-3.274-1.979H5.16zm11.24.5H8.384a.3.3 0 0 1-.155-.04L4.14 6.022a.275.275 0 0 1-.13-.315a.29.29 0 0 1 .28-.205h11.32q.086.001.156.04l4.088 2.44a.27.27 0 0 1 .13.314a.29.29 0 0 1-.28.205M8.65 17.998h10.165l-3.288-2H5.2zm-.26.5a.3.3 0 0 1-.155-.04l-4.089-2.44a.275.275 0 0 1-.13-.315a.29.29 0 0 1 .28-.205h11.32a.34.34 0 0 1 .156.04l4.088 2.44a.27.27 0 0 1 .13.314a.29.29 0 0 1-.28.205zm3.608-4.499a1.997 1.997 0 0 1-2.009-1.99a2 2 0 0 1 1.99-2.008h.02a1.98 1.98 0 0 1 1.998 1.979a1.996 1.996 0 0 1-1.979 2.019z");
}

</style>
