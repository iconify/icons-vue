<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="j08680byf"/><path class="itgjopbhc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:3d-collection" /></template>
<style>
.itgjopbhc {
  d: path("M41.007 14.801L24 4.5L6.993 14.801M24 43.5l17.007-10.098v-18.6l-9.567 4.627v8.659l-5.846 3.188v5.315L24 37.594l-1.594-1.003v-5.315l-5.846-3.188v-8.659l-9.567-4.628v18.601z");
}

.j08680byf {
  d: path("M16.56 19.43L24 14.8l7.44 4.628");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
