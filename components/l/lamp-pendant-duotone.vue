<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="ey4tq100m"/><path class="h0ob07a9s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:lamp-pendant-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ey4tq100m {
  d: path("M232 176H24a104 104 0 0 1 64-96v-8a8 8 0 0 1 8-8h64a8 8 0 0 1 8 8v8a104 104 0 0 1 64 96");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h0ob07a9s {
  d: path("M176 74.78V72a16 16 0 0 0-16-16h-24V16a8 8 0 0 0-16 0v40H96a16 16 0 0 0-16 16v2.78A111.73 111.73 0 0 0 16 176a8 8 0 0 0 8 8h64a40 40 0 0 0 80 0h64a8 8 0 0 0 8-8a111.73 111.73 0 0 0-64-101.22M128 208a24 24 0 0 1-24-24h48a24 24 0 0 1-24 24m-95.67-40a95.79 95.79 0 0 1 58.75-80.65A8 8 0 0 0 96 80v-8h64v8a8 8 0 0 0 4.92 7.38A95.79 95.79 0 0 1 223.67 168Z");
}

</style>
