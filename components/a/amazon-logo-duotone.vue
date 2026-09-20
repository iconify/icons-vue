<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="d2lgnbbhc"/><path class="z7f224btz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:amazon-logo-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d2lgnbbhc {
  d: path("M168 132a44 44 0 1 1-44-44a44 44 0 0 1 44 44");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z7f224btz {
  d: path("M248 168v32a8 8 0 0 1-16 0v-12.69l-2.21 2.22C226.69 192.9 189.44 232 128 232c-62.84 0-100.38-40.91-101.95-42.65A8 8 0 0 1 38 178.65c.27.35 34.5 37.35 90 37.35s89.73-37 90.07-37.36a4 4 0 0 1 .27-.3l2.35-2.34H208a8 8 0 0 1 0-16h32a8 8 0 0 1 8 8m-88-73.47V84a36 36 0 0 0-68.08-16.36a8 8 0 0 1-14.25-7.28A52 52 0 0 1 176 84v92a8 8 0 0 1-16 0v-6.53a52 52 0 1 1 0-74.94m0 37.47a36 36 0 1 0-36 36a36 36 0 0 0 36-36");
}

</style>
