<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="a7gu8loug"/><path class="jsbw1bbme"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-badge-left-duotone-round" /></template>
<style>
.a7gu8loug {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M18 19h-6c-.763 0-1.479-.48-2-1l-5-5a1.415 1.415 0 0 1 0-2l5-5c.521-.52 1.237-1 2-1h6c.738 0 1.369.631 1 1l-5 5a1.415 1.415 0 0 0 0 2l5 5c.369.369-.262 1-1 1");
}

.ft5dv1b6b {
  fill: none;
}

.jsbw1bbme {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 19h3c.738 0 1.369-.631 1-1l-5-5a1.414 1.414 0 0 1 0-2l5-5c.369-.369-.262-1-1-1h-6c-.64 0-1.36.36-2 1l-5 5a1.414 1.414 0 0 0 0 2l5 5c.64.64 1.36 1 2 1z");
}

</style>
