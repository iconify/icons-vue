<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lx_5dtbzi"/><path class="wxe2_ouwj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:award-duocolor-round" /></template>
<style>
.lx_5dtbzi {
  stroke-opacity: 0.4;
  d: path("m14 15l1 3c.369 1.107-.262 2.369-1 2l-2-1l-2 1c-.738.369-1.369-.893-1-2l1-3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wxe2_ouwj {
  d: path("M6 9a6 6 0 1 0 12 0A6 6 0 0 0 6 9");
}

</style>
