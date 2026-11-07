<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p-5wxgbii"/><path class="n2fd4jruh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-off-duocolor-sharp" /></template>
<style>
.n2fd4jruh {
  d: path("M12 19H3V5h2m6 0h10v10m-2 4h-7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p-5wxgbii {
  stroke-opacity: 0.4;
  d: path("m16 10l5-5M2 2l20 20");
}

</style>
