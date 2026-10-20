<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="qgmuglbms"/><path class="q6v4-u1_b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flip-3-horizontal-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q6v4-u1_b {
  d: path("M2 5L22 5M5.2929 1.7071L2 5L5.2929 8.2929M18.7071 1.7071L22 5L18.7071 8.2929M10 11L10 22L2 22ZM14 11L14 22L22 22Z");
}

.qgmuglbms {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M11 11L11 22C11 22.5523 10.5523 23 10 23L2 23C1.4477 23 1 22.5523 1 22C1 21.7887 1.067 21.5827 1.1913 21.4118L9.1913 10.4118C9.3794 10.1531 9.6801 10 10 10C10.5523 10 11 10.4477 11 11ZM13 11C13 10.4477 13.4477 10 14 10C14.3199 10 14.6206 10.1531 14.8087 10.4118L22.8087 21.4118C22.933 21.5827 23 21.7887 23 22C23 22.5523 22.5523 23 22 23L14 23C13.4477 23 13 22.5523 13 22L13 11Z");
  stroke: none;
}

</style>
