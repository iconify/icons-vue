<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r_8f1kudd"/><path class="r21jxhxfq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:container-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r_8f1kudd {
  stroke-opacity: 0.4;
  d: path("M8 5v14m4-14v14m4-14v14");
}

.r21jxhxfq {
  d: path("M3 5h18v14H3Z");
}

</style>
