<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cv5o3tbzk"/><path class="t2sx2dbpg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-big-up-duotone-sharp" /></template>
<style>
.cv5o3tbzk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 20v-8H4l8-8l8 8h-5v8Z");
}

.ft5dv1b6b {
  fill: none;
}

.t2sx2dbpg {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 20H9v-8H4l8-8l8 8h-5v8z");
}

</style>
