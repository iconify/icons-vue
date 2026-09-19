<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l8mtbua6w"/><path class="u1-iqscuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:developerwidget" /></template>
<style>
.l8mtbua6w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11 34.972V40.9a2.61 2.61 0 0 0 2.6 2.6h20.8a2.61 2.61 0 0 0 2.6-2.6V7.1a2.61 2.61 0 0 0-2.6-2.6H13.6A2.61 2.61 0 0 0 11 7.1v5.928");
}

.u1-iqscuv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.926 31.947L20.873 24l-7.947-7.947m7.947 15.894h8.857");
}

</style>
