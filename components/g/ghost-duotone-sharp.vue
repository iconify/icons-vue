<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="oxlevfbzg"/><path class="p49uikb1r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ghost-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.oxlevfbzg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M20 11v8c0 .738-.631 1.369-1 1l-1-1a2.83 2.83 0 0 0-4 0a2.83 2.83 0 0 1-4 0a2.83 2.83 0 0 0-4 0l-1 1c-.369.369-1-.262-1-1v-8a8 8 0 0 1 16 0");
}

.p49uikb1r {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 11a8 8 0 1 1 16 0v8c0 .738-.631 1.369-1 1l-1-1a2.83 2.83 0 0 0-4 0a2.83 2.83 0 0 1-4 0a2.83 2.83 0 0 0-4 0l-1 1c-.369.369-1-.262-1-1zm5-1h.01M15 10h.01");
}

</style>
