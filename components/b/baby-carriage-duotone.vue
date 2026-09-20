<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="jzazk07rp"/><path class="u7o3i0brt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:baby-carriage-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jzazk07rp {
  d: path("M232 112h-88V48a8 8 0 0 1 8-8h8a72 72 0 0 1 72 72");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.u7o3i0brt {
  d: path("M160 32h-8a16 16 0 0 0-16 16v56H55.2A40.07 40.07 0 0 0 16 72a8 8 0 0 0 0 16a24 24 0 0 1 24 24a80.09 80.09 0 0 0 80 80h40a80 80 0 0 0 0-160m63.48 72h-56.67l41.86-33.49A63.73 63.73 0 0 1 223.48 104M160 48a63.6 63.6 0 0 1 36.69 11.61L152 95.35V48Zm0 128h-40a64.09 64.09 0 0 1-63.5-56h167a64.09 64.09 0 0 1-63.5 56m-56 48a16 16 0 1 1-16-16a16 16 0 0 1 16 16m104 0a16 16 0 1 1-16-16a16 16 0 0 1 16 16");
}

</style>
