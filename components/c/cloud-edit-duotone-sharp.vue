<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="afngq-b6l"/><path class="md_vo2bpk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-edit-duotone-sharp" /></template>
<style>
.afngq-b6l {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 19A5 5 0 0 1 7 9c2-7 11-6 11 2a4 4 0 0 1 0 8Z");
}

.ft5dv1b6b {
  fill: none;
}

.md_vo2bpk {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 19A5 5 0 0 1 7 9c2-7 11-6 11 2a4 4 0 1 1 0 8Zm2-3v-2l4-4l2 2l-4 4Z");
}

</style>
