<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="a-6bkrb8q"/><path class="a14y44bqu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fuse-duotone-sharp" /></template>
<style>
.a-6bkrb8q {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 3h14v3h-2v12h2v3H5v-3h2V6H5Z");
}

.a14y44bqu {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 3h14v3h-2v12h2v3H5v-3h2V6H5zm8 5l-3 4h4l-3 4");
}

.ft5dv1b6b {
  fill: none;
}

</style>
