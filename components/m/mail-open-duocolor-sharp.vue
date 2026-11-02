<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o56uuxb3r"/><path class="iqhp1dbuy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-open-duocolor-sharp" /></template>
<style>
.iqhp1dbuy {
  d: path("m12 3l9 6v12H3V9z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o56uuxb3r {
  stroke-opacity: 0.4;
  d: path("m3 9l6 6h6l6-6");
}

</style>
