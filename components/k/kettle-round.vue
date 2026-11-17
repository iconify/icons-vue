<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z4vj06b6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:kettle-round" /></template>
<style>
.z4vj06b6s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16 10v3a4 4 0 0 1-4 4h-1a4 4 0 0 1-4-4V7c0-.64-.36-1.36-1-2L5 4c-.369-.369.262-1 1-1h6a4 4 0 0 1 4 4zm0-3h2a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2h-2M6 21h12");
}

</style>
