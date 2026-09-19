<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nnfuwabty"/><path class="y6uz-9cuf"/><circle class="yhi0vybfd"/><path class="s5zfo4b4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bedriver" /></template>
<style>
.nnfuwabty {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.562 23.821a7.8 7.8 0 1 1 13.275-8.195a7.8 7.8 0 0 1-13.275 8.196");
}

.s5zfo4b4a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.318 32.967v4.213m-9.315 0v-6.36h1.431a2.78 2.78 0 0 1 2.782 2.783v.795a2.78 2.78 0 0 1-2.782 2.782zm6.016-2.623c0-.878.711-1.59 1.59-1.59m-1.59 0v4.213");
}

.y6uz-9cuf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.7 26.479a7.8 7.8 0 1 1 3.9-6.755m-15.599 0H39.6m-31.2-.001V5.5m23.057 30.878a1.59 1.59 0 0 1-2.971-.787v-1.034a1.59 1.59 0 1 1 3.18 0v.517h-3.18m4.921-.517c0-.878.712-1.59 1.59-1.59m-1.59 0v4.213m-6.201-4.213l-1.59 4.213l-1.589-4.213");
}

.yhi0vybfd {
  cx: 22.318px;
  cy: 31.02px;
  r: 0.75px;
  fill: currentColor;
}

</style>
