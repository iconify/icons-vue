<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="w8v_i0bmu"/><path class="bo45s9bzw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-badge-up-duotone-round" /></template>
<style>
.bo45s9bzw {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 15v3c0 .738-.631 1.369-1 1l-5-5a1.414 1.414 0 0 0-2 0l-5 5c-.369.369-1-.262-1-1v-6c0-.64.36-1.36 1-2l5-5a1.414 1.414 0 0 1 2 0l5 5c.64.64 1 1.36 1 2z");
}

.ft5dv1b6b {
  fill: none;
}

.w8v_i0bmu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19 18c0 .738-.631 1.369-1 1l-5-5a1.415 1.415 0 0 0-2 0l-5 5c-.369.369-1-.262-1-1v-6c0-.763.48-1.479 1-2l5-5a1.415 1.415 0 0 1 2 0l5 5c.52.521 1 1.237 1 2Z");
}

</style>
