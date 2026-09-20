<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="sjkqsmvve"/><path class="jsncbqaja"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:list-plus-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jsncbqaja {
  d: path("M32 64a8 8 0 0 1 8-8h176a8 8 0 0 1 0 16H40a8 8 0 0 1-8-8m8 72h176a8 8 0 0 0 0-16H40a8 8 0 0 0 0 16m104 48H40a8 8 0 0 0 0 16h104a8 8 0 0 0 0-16m88 0h-16v-16a8 8 0 0 0-16 0v16h-16a8 8 0 0 0 0 16h16v16a8 8 0 0 0 16 0v-16h16a8 8 0 0 0 0-16");
}

.sjkqsmvve {
  d: path("M216 64v128H40V64Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
