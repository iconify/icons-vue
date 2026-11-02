<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xfury6v5a"/><path class="marpp3b0h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:certificate-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.marpp3b0h {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 17H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v12M7 7h10M7 11h2m4 4a2.828 2.828 0 1 1 4-4a2.828 2.828 0 0 1-4 4m0 0v6l2-2l2 2v-6");
}

.xfury6v5a {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 3h14a2 2 0 0 1 2 2v10a2 2 0 0 1-2 2h-2v4l-2-2l-2 2v-4H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2m12 14v-2h-4v2Z");
}

</style>
