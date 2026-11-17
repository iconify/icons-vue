<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g7hud0ren"/><path class="zud699bhj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:apple-logo-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g7hud0ren {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 5a2 2 0 0 1 2-2a2 2 0 0 1-2 2m7 5c-1.169.585-1.999 1.656-2 3c0 2 1 3 3 4c-.678 1.355-2.253 3.998-4 4c-1.5 0-2.5-1-4-1s-2.5 1-4 1c-2 0-4-4-4-8c0-2.5 1.5-5 4-5c1.5 0 3 1 4 1s2.5-1 4-1c1.346.001 2.297.947 3 2");
}

.zud699bhj {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 5a2 2 0 0 1 2-2a2 2 0 0 1-2 2m0 4c-1 0-2.5-1-4-1c-2.5 0-4 2.5-4 5c0 4 2 8 4 8c1.5 0 2.5-1 4-1s2.5 1 4 1s3-2 4-4c-2-1-3-2-3-4c0-1.5 1-2.5 2-3c-1-1.5-2-2-3-2c-1.5 0-3 1-4 1");
}

</style>
