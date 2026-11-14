<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hpfflob7o"/><path class="sfpr_2uud"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:data-dedupe" /></template>
<style>
.hpfflob7o {
  d: path("M6 6h12v11H6Z");
}

.sfpr_2uud {
  d: path("M3 14V5a2 2 0 0 1 2-2h10m0 17.25h6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
