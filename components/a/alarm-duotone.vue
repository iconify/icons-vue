<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="qa0d2tb3n"/><path class="tdp8u1bxy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:alarm-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.qa0d2tb3n {
  d: path("M216 136a88 88 0 1 1-88-88a88 88 0 0 1 88 88");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tdp8u1bxy {
  d: path("M128 40a96 96 0 1 0 96 96a96.11 96.11 0 0 0-96-96m0 176a80 80 0 1 1 80-80a80.09 80.09 0 0 1-80 80M61.66 37.66l-32 32a8 8 0 0 1-11.32-11.32l32-32a8 8 0 0 1 11.32 11.32m176 32a8 8 0 0 1-11.32 0l-32-32a8 8 0 0 1 11.32-11.32l32 32a8 8 0 0 1 0 11.32M184 128a8 8 0 0 1 0 16h-56a8 8 0 0 1-8-8V80a8 8 0 0 1 16 0v48Z");
}

</style>
