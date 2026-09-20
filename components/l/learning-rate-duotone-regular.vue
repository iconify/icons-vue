<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p_6ay3b_h"/><path class="dv40gzb0l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:learning-rate-duotone-regular" /></template>
<style>
.dv40gzb0l {
  d: path("M3 5h5v5h5v5h5v5h3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p_6ay3b_h {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 5h5v5h5v5h5v5h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
