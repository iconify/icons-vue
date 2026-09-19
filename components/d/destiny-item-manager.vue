<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xjhlh8btn"/><path class="b9wkx2bql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:destiny-item-manager" /></template>
<style>
.b9wkx2bql {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 19.757l4.313 4.313L24 28.384l-4.313-4.314z");
}

.xjhlh8btn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.9 24L24 36.9L11.1 24l8.6-8.6l-4.3-4.3L2.5 24L24 45.5L45.5 24L24 2.5l-4.3 4.3z");
}

</style>
