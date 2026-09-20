<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="z30u_6b6k"/><path class="d6o_ccoql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:delta-duotone-regular" /></template>
<style>
.d6o_ccoql {
  d: path("m3 17 9 -9 9 9Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.z30u_6b6k {
  fill: currentColor;
  d: path("m3 17 9 -9 9 9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
