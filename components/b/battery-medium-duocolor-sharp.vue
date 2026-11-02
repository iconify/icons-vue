<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ixsm1h1zh"/><path class="msnx-d8eh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:battery-medium-duocolor-sharp" /></template>
<style>
.ixsm1h1zh {
  stroke-opacity: 0.4;
  d: path("M6 10v4m3-4v4");
}

.msnx-d8eh {
  d: path("M3 7h15v10H3Zm18 3v4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
