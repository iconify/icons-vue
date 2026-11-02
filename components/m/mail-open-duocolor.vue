<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x375nxb3k"/><path class="gmsa2q7zv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-open-duocolor" /></template>
<style>
.gmsa2q7zv {
  d: path("M12 21H5a2 2 0 0 1-2-2V9l6-4a5.41 5.41 0 0 1 6 0l6 4v10a2 2 0 0 1-2 2z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x375nxb3k {
  stroke-opacity: 0.4;
  d: path("m3 9l5 5c.64.64 1.36 1 2 1h4c.64 0 1.36-.36 2-1l5-5");
}

</style>
