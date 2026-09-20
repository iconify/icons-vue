<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="p02vr_beq"/><path class="xedf9ccsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:bookmark-off" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.p02vr_beq {
  fill-rule: evenodd;
  d: path("m6.245 17.667l3.755-4.2l3.755 4.2c.611.684 1.745.251 1.745-.667V3a1 1 0 0 0-1-1h-9a1 1 0 0 0-1 1v14c0 .918 1.134 1.35 1.745.666M6.5 14.38V4h7v10.381l-2.754-3.08a1 1 0 0 0-1.491 0z");
}

.xedf9ccsf {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
