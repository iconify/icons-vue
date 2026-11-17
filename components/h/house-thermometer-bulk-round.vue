<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="o3cwdvb-i"/><path class="vt-3ibbsu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-thermometer-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.o3cwdvb-i {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 22H8a5 5 0 0 1-5-5v-5.185a5 5 0 0 1 1.707-3.763l4-3.5a5 5 0 0 1 6.586 0l4 3.5A5 5 0 0 1 21 11.815V17a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 22");
}

.vt-3ibbsu {
  d: path("M11.5 9.5v4.373a1 1 0 0 1-.333.745a1.25 1.25 0 0 0-.051 1.816a1.248 1.248 0 0 0 2.134-.884a1.25 1.25 0 0 0-.417-.932a1 1 0 0 1-.333-.745V9.5a.5.5 0 0 0-1 0m-2 3.973V9.5a2.5 2.5 0 1 1 5 0v3.973a3.249 3.249 0 0 1-4.727 4.444a3.25 3.25 0 0 1-.273-4.444");
}

</style>
