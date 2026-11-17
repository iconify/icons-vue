<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zsyg7ybrk"/><path class="iv_t2mbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lamp-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.iv_t2mbnq {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 11H7c-.919 0-1.46-1.081-1-2l2-4c.613-1.226 1.387-2 2-2h4c.613 0 1.387.774 2 2l2 4c.46.919-.081 2-1 2zm0 0v6m-4 2a2 2 0 0 1 2-2h4a2 2 0 1 1 0 4h-4a2 2 0 0 1-2-2");
}

.zsyg7ybrk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17 11H7c-.919 0-1.459-1.081-1-2l2-4c.326-.651 1.15-1.999 2-2h4c.85.001 1.674 1.349 2 2l2 4c.459.919-.081 2-1 2m-7 6h4a2 2 0 1 1 0 4h-4a2 2 0 1 1 0-4");
}

</style>
