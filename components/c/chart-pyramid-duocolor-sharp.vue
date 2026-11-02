<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zz-38cczo"/><path class="ifdryrb5s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-pyramid-duocolor-sharp" /></template>
<style>
.ifdryrb5s {
  d: path("m16 11l5 10H3l9-18z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zz-38cczo {
  stroke-opacity: 0.4;
  d: path("M9 9h6m-9 6h12");
}

</style>
