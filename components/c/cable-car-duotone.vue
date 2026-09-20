<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="q1_mb4bpj"/><path class="l1vv7xpdu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:cable-car-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.l1vv7xpdu {
  d: path("M247.87 30.59a8 8 0 0 0-9.28-6.46l-224 40A8 8 0 0 0 16 80a8.6 8.6 0 0 0 1.42-.12L120 61.56V96H64a32 32 0 0 0-32 32v64a32 32 0 0 0 32 32h128a32 32 0 0 0 32-32v-64a32 32 0 0 0-32-32h-56V58.7l105.4-18.82a8 8 0 0 0 6.47-9.29M104 160v-48h48v48Zm-40-48h24v48H48v-32a16 16 0 0 1 16-16m128 96H64a16 16 0 0 1-16-16v-16h160v16a16 16 0 0 1-16 16m16-80v32h-40v-48h24a16 16 0 0 1 16 16");
}

.q1_mb4bpj {
  d: path("M216 128v40H40v-40a24 24 0 0 1 24-24h128a24 24 0 0 1 24 24");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
