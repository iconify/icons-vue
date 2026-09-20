<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="wkhltsbwr"/><path class="voclqol9t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:highlighter-circle-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.voclqol9t {
  d: path("M201.54 54.46A104 104 0 0 0 54.46 201.54A104 104 0 0 0 201.54 54.46M96 210v-58h64v58a88.33 88.33 0 0 1-64 0m48-74h-32v-35.06l32-16Zm46.22 54.22A88 88 0 0 1 176 201.77V152a16 16 0 0 0-16-16V72a8 8 0 0 0-11.58-7.16l-48 24A8 8 0 0 0 96 96v40a16 16 0 0 0-16 16v49.77a88 88 0 1 1 110.22-11.55");
}

.wkhltsbwr {
  d: path("M195.88 195.88A95.7 95.7 0 0 1 168 215.29V152a8 8 0 0 0-8-8h-8V72l-48 24v48h-8a8 8 0 0 0-8 8v63.29a96 96 0 1 1 107.88-19.41");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
