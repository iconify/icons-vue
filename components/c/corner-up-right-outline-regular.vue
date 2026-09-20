<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uhkbmlahb"/><path class="vmh-l_baq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:corner-up-right-outline-regular" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uhkbmlahb {
  d: path("M4 20V10h16");
}

.vmh-l_baq {
  d: path("m15 5 5 5 -5 5");
}

</style>
