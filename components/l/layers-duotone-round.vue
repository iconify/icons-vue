<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cr9pmab7h"/><path class="q6bcw4b7e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:layers-duotone-round" /></template>
<style>
.cr9pmab7h {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m12 4l6 3a1.118 1.118 0 0 1 0 2l-6 3l-6-3a1.118 1.118 0 0 1 0-2Z");
}

.ft5dv1b6b {
  fill: none;
}

.q6bcw4b7e {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m8 6l4-2l6 3a1.118 1.118 0 0 1 0 2l-6 3l-6-3a1.118 1.118 0 0 1 0-2zm-4 6l8 4l8-4M4 16l8 4l8-4");
}

</style>
