<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e3ib2mtgj"/><path class="cjijt9ufn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bejeweled-stars" /></template>
<style>
.cjijt9ufn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.8 39L14 17l2-4l8-3.7m-9.754 2.087L16 13m8.2 26L34 17l-2-4l-8-3.7m11.808.2L32.001 13M11.99 4.446L13.145 8h3.737l-3.024 2.197l1.155 3.555l-3.024-2.197l-3.024 2.197l1.155-3.555L7.098 8h3.737Zm22.855 26.5L36 34.5h3.737l-3.023 2.197l1.155 3.554l-3.024-2.197l-3.024 2.197l1.155-3.554l-3.023-2.197h3.737Z");
}

.e3ib2mtgj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9.701 11.492l-4.879 4.877a1.1 1.1 0 0 0-.057 1.496L23.164 39.32a1.1 1.1 0 0 0 1.672 0l18.398-21.455a1.1 1.1 0 0 0-.057-1.496L35.806 9H15.505M5 17.15h38.5");
}

</style>
