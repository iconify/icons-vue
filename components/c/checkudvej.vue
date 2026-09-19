<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="xlh6bfj6w"/><path class="xsfjkbbel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:checkudvej" /></template>
<style>
.xlh6bfj6w {
  width: 26.419px;
  height: 39px;
  x: 10.79px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.553px;
}

.xsfjkbbel {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m37.2 41.12l-14.06-4.178a2.52 2.52 0 0 1-1.8-2.412V13.47a2.52 2.52 0 0 1 1.8-2.412L37.2 6.88M24.621 25.954v-3.908");
}

</style>
