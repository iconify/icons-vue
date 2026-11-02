<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ye2-fvvej"/><path class="b2_xccbks"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:list-collapse-duocolor-round" /></template>
<style>
.b2_xccbks {
  d: path("M13 6h8m-8 6h8m-8 6h8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ye2-fvvej {
  stroke-opacity: 0.4;
  d: path("m3 6l3 3l3-3m0 12l-3-3l-3 3");
}

</style>
