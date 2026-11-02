<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r_lyfv-an"/><path class="erpvbebac"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fold-vertical-duocolor" /></template>
<style>
.erpvbebac {
  d: path("m9 7l3 3l3-3m-3 3V3m3 14l-3-3l-3 3m3-3v7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r_lyfv-an {
  stroke-opacity: 0.4;
  d: path("M4 12h4m8 0h4");
}

</style>
