<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tnryyv3mu"/><path class="tp9nqccpz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:download-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tnryyv3mu {
  stroke-opacity: 0.4;
  d: path("M4 16v4h16v-4");
}

.tp9nqccpz {
  d: path("m8 12l4 4l4-4m-4 4V4");
}

</style>
