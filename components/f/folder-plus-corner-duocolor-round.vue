<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="m0z_pzvrc"/><path class="qravvf8eg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-plus-corner-duocolor-round" /></template>
<style>
.m0z_pzvrc {
  stroke-opacity: 0.4;
  d: path("M13 17h8m-4-4v8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qravvf8eg {
  d: path("M12 6h7a2 2 0 0 1 2 2M8 20H7a4 4 0 0 1-4-4V6a2 2 0 0 1 2-2h5l2 2");
}

</style>
