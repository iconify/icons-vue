<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="azynadcet"/><path class="srcn-pb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-big-down-duotone" /></template>
<style>
.azynadcet {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 4h4a1 1 0 0 1 1 1v6a1 1 0 0 0 1 1h3c.369 0 .369.631 0 1l-6 6a1.415 1.415 0 0 1-2 0l-6-6c-.369-.369-.369-1 0-1h3a1 1 0 0 0 1-1V5a1 1 0 0 1 1-1");
}

.ft5dv1b6b {
  fill: none;
}

.srcn-pb8s {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 4h-2a1 1 0 0 0-1 1v6a1 1 0 0 1-1 1H5c-.369 0-.369.631 0 1l6 6a1.414 1.414 0 0 0 2 0l6-6c.369-.369.369-1 0-1h-3a1 1 0 0 1-1-1V5a1 1 0 0 0-1-1z");
}

</style>
