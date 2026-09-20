<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGJ7pSldCd)" class="r4i437pya"/><path class="s346nrmku"/></g><defs><linearGradient id="SVGJ7pSldCd" x1="6.181" x2="19.019" y1="3.429" y2="19.86" gradientUnits="userSpaceOnUse"><stop class="e05jcvhqi"/><stop offset="1" class="iihd5kbqv"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:btse-background" /></template>
<style>
.e05jcvhqi {
  stop-color: var(--svg-color--007cd0, #007cd0);
}

.ft5dv1b6b {
  fill: none;
}

.iihd5kbqv {
  stop-color: var(--svg-color--004eae, #004eae);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.s346nrmku {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.332 16.8c1.357 0 2.139-.687 2.139-1.6c0-.846-.69-1.6-2.186-1.6H9.333v3.2zm-.599-6.4c1.358 0 2.07-.688 2.07-1.6c0-.845-.735-1.6-2.07-1.6h-2.4v3.2zM5.067 4h7.724c2.024 0 3.451.699 4.394 1.611c.644.624 1.035 1.448 1.035 2.516v.044c0 1.803-1.058 2.871-2.484 3.473c1.955.623 3.197 1.691 3.197 3.806v.044c0 2.672-2.254 4.506-6.096 4.506h-7.77z");
}

</style>
