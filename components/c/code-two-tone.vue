<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zc4q38k8f"/><path class="mii5dhp2e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:code-two-tone" /></template>
<style>
.mii5dhp2e {
  d: path("M16 5L22 12L16 19");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zc4q38k8f {
  stroke-opacity: 0.4;
  d: path("M8 5L2 12L8 19");
}

</style>
