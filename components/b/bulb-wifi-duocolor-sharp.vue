<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k_zqh9hij"/><path class="qitkaw-0j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bulb-wifi-duocolor-sharp" /></template>
<style>
.k_zqh9hij {
  stroke-opacity: 0.4;
  d: path("M6 21h4m3.657-14.657A8 8 0 0 1 16 12m.485-8.485A12 12 0 0 1 20 12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qitkaw-0j {
  d: path("M10 16v2H6v-2c0-1-2-2.33-2-4a4 4 0 1 1 8 0c0 1.67-2 3-2 4");
}

</style>
