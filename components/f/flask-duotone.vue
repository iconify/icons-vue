<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wow4c0btq"/><path class="mr7hqq0qk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flask-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mr7hqq0qk {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 3v6L5 19c-.46.919.081 2 1 2h12c.919 0 1.46-1.081 1-2L14 9V3M8 3h8M7 15h10");
}

.wow4c0btq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17 14c.379 0 .725.214.894.553l2 4c.181.356.274.75.273 1.149C20.164 20.924 19.265 22 18 22H6c-1.265 0-2.164-1.076-2.167-2.298a2.5 2.5 0 0 1 .273-1.149l2-4A1 1 0 0 1 7 14Z");
}

</style>
