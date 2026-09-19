<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b4cis-blo"/><path class="a6oakh54w"/><path class="v5hoh4peo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:arena" /></template>
<style>
.a6oakh54w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.18 41.2A76.4 76.4 0 0 0 43.5 30.52S28.72 20.58 24 6.8C19.28 20.58 4.5 30.52 4.5 30.52A76.4 76.4 0 0 0 17.82 41.2");
}

.b4cis-blo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 31.07c-3.44-4.52-9.75-9-9.75-9");
}

.v5hoh4peo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 31.07c3.44-4.52 9.75-9 9.75-9");
}

</style>
