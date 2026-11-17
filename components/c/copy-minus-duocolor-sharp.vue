<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qofgq8btb"/><path class="fa94ixb2z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:copy-minus-duocolor-sharp" /></template>
<style>
.fa94ixb2z {
  d: path("M7 3h14v14H7ZM3 9v12h12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qofgq8btb {
  stroke-opacity: 0.4;
  d: path("M11 10h6");
}

</style>
