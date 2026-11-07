<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pnc_lns1w"/><path class="bsyq0zp1v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-plus-duocolor-sharp" /></template>
<style>
.bsyq0zp1v {
  d: path("M21 13v6H3V5h8M3 5l6 6h4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pnc_lns1w {
  stroke-opacity: 0.4;
  d: path("M15 6h6m-3-3v6");
}

</style>
