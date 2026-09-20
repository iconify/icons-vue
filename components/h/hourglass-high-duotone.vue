<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="hehn99h5q"/><path class="fcp16tyfb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:hourglass-high-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fcp16tyfb {
  d: path("M184 24H72a16 16 0 0 0-16 16v36a16.07 16.07 0 0 0 6.4 12.8l52.27 39.2l-52.27 39.2A16.07 16.07 0 0 0 56 180v36a16 16 0 0 0 16 16h112a16 16 0 0 0 16-16v-35.64a16.09 16.09 0 0 0-6.35-12.77L141.27 128l52.38-39.59A16.09 16.09 0 0 0 200 75.64V40a16 16 0 0 0-16-16m0 16v16H72V40Zm0 176H72v-36l56-42l56 42.35Zm-56-98L72 76v-4h112v3.64Z");
}

.hehn99h5q {
  d: path("M192 64v11.64a8 8 0 0 1-3.18 6.36L128 128L67.2 82.4A8 8 0 0 1 64 76V64Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
