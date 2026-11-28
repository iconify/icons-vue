<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="e946dwmoc"/><path class="qib3ujb7r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:iframe-off-sharp-fill" /></template>
<style>
.e946dwmoc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.707 17.707C17.526 17.888 17.276 18 17 18H7C6.448 18 6 17.552 6 17V13C6 12.448 6.448 12 7 12H12L17.707 17.707ZM10 10H4V20H20L21.707 21.707C21.526 21.888 21.276 22 21 22H3C2.448 22 2 21.552 2 21V3C2 2.724 2.112 2.474 2.293 2.293L10 10ZM15.657 12H17C17.552 12 18 12.448 18 13V14.343L15.657 12ZM20 16.343V10H13.657L5.657 2H12H21C21.552 2 22 2.448 22 3V18.343L20 16.343Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qib3ujb7r {
  d: path("M1.707 1.707L22.293 22.293");
}

</style>
