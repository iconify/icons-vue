<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="ftcj0fkzg"/><path class="wo6sb-8cu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrows-out-line-vertical-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ftcj0fkzg {
  d: path("M216 32v192a16 16 0 0 1-16 16H56a16 16 0 0 1-16-16V32a16 16 0 0 1 16-16h144a16 16 0 0 1 16 16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wo6sb-8cu {
  d: path("M224 128a8 8 0 0 1-8 8H40a8 8 0 0 1 0-16h176a8 8 0 0 1 8 8M101.66 53.66L120 35.31V96a8 8 0 0 0 16 0V35.31l18.34 18.35a8 8 0 0 0 11.32-11.32l-32-32a8 8 0 0 0-11.32 0l-32 32a8 8 0 0 0 11.32 11.32m52.68 148.68L136 220.69V160a8 8 0 0 0-16 0v60.69l-18.34-18.35a8 8 0 0 0-11.32 11.32l32 32a8 8 0 0 0 11.32 0l32-32a8 8 0 0 0-11.32-11.32");
}

</style>
