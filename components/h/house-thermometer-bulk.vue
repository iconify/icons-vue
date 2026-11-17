<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="k0z9u4bez"/><path class="vt-3ibbsu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-thermometer-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.k0z9u4bez {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 22H6a3 3 0 0 1-3-3v-8.092c0-.866.373-1.689 1.024-2.258l6-5.25a3 3 0 0 1 3.952 0l6 5.25A3 3 0 0 1 21 10.908V19a3 3 0 0 1-3 3");
}

.vt-3ibbsu {
  d: path("M11.5 9.5v4.373a1 1 0 0 1-.333.745a1.25 1.25 0 0 0-.051 1.816a1.248 1.248 0 0 0 2.134-.884a1.25 1.25 0 0 0-.417-.932a1 1 0 0 1-.333-.745V9.5a.5.5 0 0 0-1 0m-2 3.973V9.5a2.5 2.5 0 1 1 5 0v3.973a3.249 3.249 0 0 1-4.727 4.444a3.25 3.25 0 0 1-.273-4.444");
}

</style>
