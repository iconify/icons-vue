<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="e1dma4b7w"/><path class="edmezdkmt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:folder-notch-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.e1dma4b7w {
  d: path("m128 80l-29.87 22.4a8 8 0 0 1-4.8 1.6H32V64a8 8 0 0 1 8-8h53.33a8 8 0 0 1 4.8 1.6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.edmezdkmt {
  d: path("M216 72h-85.33l-27.74-20.8a16.12 16.12 0 0 0-9.6-3.2H40a16 16 0 0 0-16 16v136a16 16 0 0 0 16 16h176a16 16 0 0 0 16-16V88a16 16 0 0 0-16-16M40 64h53.33l21.34 16l-21.34 16H40Zm176 136H40v-88h53.33a16.12 16.12 0 0 0 9.6-3.2L130.67 88H216Z");
}

</style>
