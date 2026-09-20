<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="q-xw23bit"/><path class="fx-72r-qu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:chair-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fx-72r-qu {
  d: path("M208 136h-32v-32h16a16 16 0 0 0 16-16V40a16 16 0 0 0-16-16H64a16 16 0 0 0-16 16v48a16 16 0 0 0 16 16h16v32H48a16 16 0 0 0-16 16v16a16 16 0 0 0 16 16h8v40a8 8 0 0 0 16 0v-40h112v40a8 8 0 0 0 16 0v-40h8a16 16 0 0 0 16-16v-16a16 16 0 0 0-16-16M64 40h128v48H64Zm32 64h64v32H96Zm112 64H48v-16h160z");
}

.q-xw23bit {
  d: path("M56 88V40a8 8 0 0 1 8-8h128a8 8 0 0 1 8 8v48a8 8 0 0 1-8 8H64a8 8 0 0 1-8-8m152 56H48a8 8 0 0 0-8 8v16a8 8 0 0 0 8 8h160a8 8 0 0 0 8-8v-16a8 8 0 0 0-8-8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
