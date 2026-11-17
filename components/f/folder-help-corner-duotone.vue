<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mtieljw7a"/><path class="qdqruq15e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-help-corner-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mtieljw7a {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m10 4l2 2h7a2 2 0 0 1 2 2H10a2 2 0 0 0-2 2v10H5a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2Z");
}

.qdqruq15e {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 6h7a2 2 0 0 1 2 2M8 20H5a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h5l2 2m3 10a2 2 0 1 1 2 2m0 3h.01");
}

</style>
