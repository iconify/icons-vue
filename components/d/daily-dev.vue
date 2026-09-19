<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o705y2bvt"/><path class="slg3agbxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:daily-dev" /></template>
<style>
.o705y2bvt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.74 24l-6.37 6.369a2.8 2.8 0 1 0 3.96 3.96l8.35-8.349a2.8 2.8 0 0 0 0-3.96l-8.35-8.35a2.8 2.8 0 0 0-3.96 0L24 20.039l-6.369-6.369a2.8 2.8 0 0 0-3.96 0l-8.35 8.35a2.8 2.8 0 0 0 0 3.96l8.35 8.35a2.8 2.8 0 0 0 3.96 0l18.68-18.68l-2.51 5.411z");
}

.slg3agbxw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 20.039l-12.31 12.31l2.51-5.41L11.26 24l4.39-4.388L20.039 24");
}

</style>
