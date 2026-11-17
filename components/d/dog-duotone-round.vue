<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="p_gfogbtq"/><path class="ssmnx9b-z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:dog-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.p_gfogbtq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 5h8c.772-.771 1.947-1 3-1c1.606.002 2 1.706 2 3v4c0 1.6-.8 3-2 3l-3 5c-.709 1.181-1.534 1.999-3 2h-2c-1.466-.001-2.291-.819-3-2l-3-5c-1.2 0-2-1.4-2-3V7c0-1.294.394-2.998 2-3c1.053 0 2.228.229 3 1");
}

.ssmnx9b-z {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 5h8c.7-.7 1.8-1 3-1c1.5 0 2 1.5 2 3v4c0 1.6-.8 3-2 3l-3 5c-.6 1-1.4 2-3 2h-2c-1.6 0-2.4-1-3-2l-3-5c-1.2 0-2-1.4-2-3V7c0-1.5.5-3 2-3c1.2 0 2.3.3 3 1m0 0c-.7 3-1.5 6.5-3 9m11-9c.7 3 1.5 6.5 3 9m-9-3h.01M14 11h.01M10 14h4l-2 2Zm2 2v2");
}

</style>
