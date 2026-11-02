<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="w3_a7ebwa"/><path class="hdhvhp1sv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-sparkle-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hdhvhp1sv {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3h7a2 2 0 0 1 2 2v10a2 2 0 0 1-2 2H8c-.64 0-1.36.36-2 1l-2 2c-.369.369-1-.262-1-1V5a2 2 0 0 1 2-2zm0 3c0 2 2 4 4 4c-2 0-4 2-4 4c0-2-2-4-4-4c2 0 4-2 4-4");
}

.w3_a7ebwa {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19 3a2 2 0 0 1 2 2v10a2 2 0 0 1-2 2H8c-.763 0-1.479.48-2 1l-2 2c-.369.369-1-.262-1-1V5a2 2 0 0 1 2-2Z");
}

</style>
