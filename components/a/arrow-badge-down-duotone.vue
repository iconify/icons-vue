<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="i8tzoccit"/><path class="r32o08wtb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-badge-down-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i8tzoccit {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19 5v8l-6 6a1.415 1.415 0 0 1-2 0l-6-6V5c0-.369.631-.369 1 0l5 5a1.415 1.415 0 0 0 2 0l5-5c.369-.369 1-.369 1 0");
}

.r32o08wtb {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 9V5c0-.369-.631-.369-1 0l-5 5a1.414 1.414 0 0 1-2 0L6 5c-.369-.369-1-.369-1 0v8l6 6a1.414 1.414 0 0 0 2 0l6-6z");
}

</style>
