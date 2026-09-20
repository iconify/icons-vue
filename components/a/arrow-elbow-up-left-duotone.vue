<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="e2qzmmc2s"/><path class="br5pzzjpx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-elbow-up-left-duotone" /></template>
<style>
.br5pzzjpx {
  d: path("M192 72h-88V32a8 8 0 0 0-13.66-5.66l-48 48a8 8 0 0 0 0 11.32l48 48A8 8 0 0 0 104 128V88h80v136a8 8 0 0 0 16 0V80a8 8 0 0 0-8-8M88 108.69L59.31 80L88 51.31Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.e2qzmmc2s {
  d: path("M96 32v96L48 80Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
