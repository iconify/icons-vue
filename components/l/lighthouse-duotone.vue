<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="vnvh7hmbi"/><path class="pd7neg04v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:lighthouse-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.pd7neg04v {
  d: path("M208 80a8 8 0 0 0-8 8v16h-11.15L184 55.2a8 8 0 0 0-2.68-5.2l-42.88-38.12l-.2-.17a16 16 0 0 0-20.48 0l-.2.17L74.68 50A8 8 0 0 0 72 55.2L67.15 104H56V88a8 8 0 0 0-16 0v24a8 8 0 0 0 8 8h17.54l-9.47 94.48A16 16 0 0 0 72 232h112a16 16 0 0 0 15.92-17.56L190.46 120H208a8 8 0 0 0 8-8V88a8 8 0 0 0-8-8m-80-56l27 24h-54ZM87.24 64h81.52l4 40H136V88a8 8 0 0 0-16 0v16H83.23ZM72 216l4-40h104l4 40Zm106.39-56H77.61l4-40h92.76Z");
}

.vnvh7hmbi {
  d: path("M181.61 112H74.39L80 56h96ZM192 215.24L187.23 168H68.77L64 215.24a8 8 0 0 0 8 8.76h112a8 8 0 0 0 8-8.76");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
