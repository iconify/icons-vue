<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bpofa4q6i"/><path class="q-vekkb6p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:helicopter-duotone-round" /></template>
<style>
.bpofa4q6i {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11 17a2 2 0 0 1-2-2v-4a4 4 0 0 1 4-4c4.42 0 8 2.69 8 6a4 4 0 0 1-4 4Z");
}

.ft5dv1b6b {
  fill: none;
}

.q-vekkb6p {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 15a2 2 0 0 0 2 2h6a4 4 0 0 0 4-4c0-3.31-3.58-6-8-6a4 4 0 0 0-4 4Zm-6-2h6m-6-3v6m10 1v4m4-4v4m-8 0h12M13 7v4a2 2 0 0 0 2 2h6M5 3h16m-8 0v4");
}

</style>
