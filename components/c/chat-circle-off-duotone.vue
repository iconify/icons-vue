<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ipxt395mb"/><path class="zpr1p3bjx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-off-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ipxt395mb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9.432 3.432a8.94 8.94 0 0 1 8.893 2.244a8.94 8.94 0 0 1 2.243 8.892ZM8 20l-5 1l1-5A8.945 8.945 0 0 1 5.675 5.675l12.65 12.65A8.95 8.95 0 0 1 8 20");
}

.zpr1p3bjx {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m18 19l-2 1a8.94 8.94 0 0 1-8 0l-5 1l1-5a8.94 8.94 0 0 1 0-8l1-2m5-3a9.22 9.22 0 0 1 11 11M2 2l20 20");
}

</style>
