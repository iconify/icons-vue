<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="au2rcutys"/><path class="x136nvb7p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:article-ny-times-duotone" /></template>
<style>
.au2rcutys {
  d: path("M232 104v96H80v-32h48v-64Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cuyn6tgcc {
  fill: currentColor;
}

.x136nvb7p {
  d: path("M128 96h104a8 8 0 0 1 0 16H128a8 8 0 0 1 0-16m104 32H128a8 8 0 0 0 0 16h104a8 8 0 0 0 0-16m0 32H80a8 8 0 0 0 0 16h152a8 8 0 0 0 0-16m0 32H80a8 8 0 0 0 0 16h152a8 8 0 0 0 0-16M96 144a8 8 0 0 0 0-16h-8V64h32v8a8 8 0 0 0 16 0V56a8 8 0 0 0-8-8H32a8 8 0 0 0-8 8v16a8 8 0 0 0 16 0v-8h32v64h-8a8 8 0 0 0 0 16Z");
}

</style>
