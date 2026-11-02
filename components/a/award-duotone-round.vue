<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wqpv4acmh"/><path class="tmy95jbif"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:award-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.tmy95jbif {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 9a6 6 0 1 0 12 0A6 6 0 0 0 6 9m8 6l1 3c.369 1.107-.262 2.369-1 2l-2-1l-2 1c-.738.369-1.369-.893-1-2l1-3");
}

.wqpv4acmh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m15.14 15.258l.809 2.426c.13.392.182.805.152 1.217c-.054.772-.399 1.601-1.111 1.98c-.449.24-.983.24-1.437.013L12 20.118l-1.553.776a1.56 1.56 0 0 1-1.437-.013c-.712-.379-1.057-1.208-1.111-1.98a3.1 3.1 0 0 1 .152-1.217l.809-2.426A7.003 7.003 0 0 1 12 2a7.002 7.002 0 0 1 3.14 13.258");
}

</style>
