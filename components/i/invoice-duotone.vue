<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="qemz5voez"/><path class="i8s_v0bny"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:invoice-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.i8s_v0bny {
  d: path("M28 128a8 8 0 0 1 0-16h28a8 8 0 0 0 0-16H40a24 24 0 0 1 0-48a8 8 0 0 1 16 0h8a8 8 0 0 1 0 16H40a8 8 0 0 0 0 16h16a24 24 0 0 1 0 48a8 8 0 0 1-16 0Zm204-72v136a16 16 0 0 1-16 16H40a16 16 0 0 1-16-16v-40a8 8 0 0 1 16 0v40h120v-32H80a8 8 0 0 1 0-16h80v-32h-56a8 8 0 0 1 0-16h112V64H96a8 8 0 0 1 0-16h128a8 8 0 0 1 8 8m-56 88h40v-32h-40Zm40 48v-32h-40v32Z");
}

.qemz5voez {
  d: path("M224 104v88a8 8 0 0 1-8 8h-48v-96Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
