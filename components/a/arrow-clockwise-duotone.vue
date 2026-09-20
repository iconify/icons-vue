<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="fw_-f4u_a"/><path class="pqj_s8bcb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-clockwise-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fw_-f4u_a {
  d: path("M216 128a88 88 0 1 1-88-88a88 88 0 0 1 88 88");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pqj_s8bcb {
  d: path("M240 56v48a8 8 0 0 1-8 8h-48a8 8 0 0 1 0-16h27.4l-26.59-24.36l-.25-.24a80 80 0 1 0-1.67 114.78a8 8 0 0 1 11 11.63A95.44 95.44 0 0 1 128 224h-1.32a96 96 0 1 1 69.07-164L224 85.8V56a8 8 0 1 1 16 0");
}

</style>
