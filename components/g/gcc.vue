<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f4tndo65j"/><circle class="n49fgtbiw"/><path class="c6lj-_7pe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gcc" /></template>
<style>
.c6lj-_7pe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.696 25.537v.038a3.09 3.09 0 1 1-6.18 0v-3.149a3.09 3.09 0 1 1 6.18 0v.039m-8.594-.038a3.09 3.09 0 1 0-6.18 0v3.148a3.09 3.09 0 1 0 6.18 0h-3.09m20.278-.038v.038a3.09 3.09 0 1 1-6.18 0v-3.149a3.09 3.09 0 1 1 6.18 0v.039");
}

.f4tndo65j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M44.999 28.009A21.38 21.38 0 0 1 28.008 45M28 3a21.38 21.38 0 0 1 17 17m-42-.007A21.38 21.38 0 0 1 19.99 3.002M19.991 45A21.38 21.38 0 0 1 3 28.009");
}

.n49fgtbiw {
  cx: 23.999px;
  cy: 24.001px;
  r: 17.259px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
