<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="em034qble"/><path class="dulzitbkk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:decimal-increase-duotone-sharp" /></template>
<style>
.dulzitbkk {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 5a2 2 0 1 1 4 0v2a2 2 0 1 1-4 0Zm8 0a2 2 0 1 1 4 0v2a2 2 0 1 1-4 0ZM3 9h.01M18 21l3-3l-3-3m3 3H3");
}

.em034qble {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 5v2a3 3 0 1 1-6 0V5a3 3 0 1 1 6 0m8 0v2a3 3 0 1 1-6 0V5a3 3 0 1 1 6 0");
}

.ft5dv1b6b {
  fill: none;
}

</style>
