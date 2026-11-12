<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yxe1yactt"/><path class="w6gz7y24y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:billboard-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w6gz7y24y {
  d: path("M3 3h18v12H3Zm4 12v6m10-6v6");
}

.yxe1yactt {
  stroke-opacity: 0.4;
  d: path("M7 7h10M7 11h6");
}

</style>
