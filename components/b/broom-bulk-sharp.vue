<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mrj8dzn_y"/><path class="odthb3bgb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:broom-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.mrj8dzn_y {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 11c.379 0 .725.214.894.553l4 8A1 1 0 0 1 20 21H4a1 1 0 0 1-.894-1.447l4-8A1 1 0 0 1 8 11Z");
}

.odthb3bgb {
  d: path("M13 12a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm-4 5a1 1 0 0 1 2 0v3a1 1 0 0 1-2 0Zm4 0a1 1 0 0 1 2 0v3a1 1 0 0 1-2 0Z");
}

</style>
