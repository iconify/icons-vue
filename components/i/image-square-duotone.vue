<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="hpe3egb0r"/><path class="h_e52im_t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:image-square-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.h_e52im_t {
  d: path("M208 32H48a16 16 0 0 0-16 16v160a16 16 0 0 0 16 16h160a16 16 0 0 0 16-16V48a16 16 0 0 0-16-16M48 48h160v77.38l-24.69-24.7a16 16 0 0 0-22.62 0L53.37 208H48Zm160 160H76l96-96l36 36zM96 120a24 24 0 1 0-24-24a24 24 0 0 0 24 24m0-32a8 8 0 1 1-8 8a8 8 0 0 1 8-8");
}

.hpe3egb0r {
  d: path("M208 40H48a8 8 0 0 0-8 8v160a8 8 0 0 0 8 8h8.69l109.65-109.66a8 8 0 0 1 11.32 0L216 144.69V48a8 8 0 0 0-8-8M96 112a16 16 0 1 1 16-16a16 16 0 0 1-16 16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
