<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dax2p4b0u"/><path class="cc9-_0c2g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-check-corner-duocolor" /></template>
<style>
.cc9-_0c2g {
  d: path("M11 19H5a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v4M4 6l4 4c.64.64 1.36 1 2 1h4c.64 0 1.36-.36 2-1l4-4");
}

.dax2p4b0u {
  stroke-opacity: 0.4;
  d: path("m15 18l2 2l4-4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
