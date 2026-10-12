<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="d2efs3bol"/><path class="to8m3ibcr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:eye-scan-sharp" /></template>
<style>
.d2efs3bol {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 8V3.75H8m8 0h4.25V8m0 8v4.25H16m-8 0H3.75V16m3-4c1.2-2.3 3-3.5 5.25-3.5s4.05 1.2 5.25 3.5c-1.2 2.3-3 3.5-5.25 3.5S7.95 14.3 6.75 12Z");
}

.to8m3ibcr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
