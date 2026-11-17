<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="yulrr8b_a"/><path class="wugd8kz0k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:kettle-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.wugd8kz0k {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16 10v5a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2V6L5 4c-.369-.369-.369-1 0-1h9a2 2 0 0 1 2 2zm0-3h2a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2h-2M6 21h12");
}

.yulrr8b_a {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M16 5v10a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2V6L5 4c-.369-.369-.369-1 0-1h9a2 2 0 0 1 2 2");
}

</style>
