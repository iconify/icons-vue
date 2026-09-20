<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="lc-wsphsb"/><path class="qs2prubpb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:align-center-horizontal-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lc-wsphsb {
  d: path("M64 104V64a8 8 0 0 1 8-8h112a8 8 0 0 1 8 8v40a8 8 0 0 1-8 8H72a8 8 0 0 1-8-8m144 40H48a8 8 0 0 0-8 8v40a8 8 0 0 0 8 8h160a8 8 0 0 0 8-8v-40a8 8 0 0 0-8-8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qs2prubpb {
  d: path("M208 136h-72v-16h48a16 16 0 0 0 16-16V64a16 16 0 0 0-16-16h-48V32a8 8 0 0 0-16 0v16H72a16 16 0 0 0-16 16v40a16 16 0 0 0 16 16h48v16H48a16 16 0 0 0-16 16v40a16 16 0 0 0 16 16h72v16a8 8 0 0 0 16 0v-16h72a16 16 0 0 0 16-16v-40a16 16 0 0 0-16-16M72 64h112v40H72Zm136 128H48v-40h160z");
}

</style>
