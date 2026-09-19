<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ciw0pibus"/><path class="o0_h56dwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dl-play-box" /></template>
<style>
.ciw0pibus {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.129 33.655c0 1.71-1.201 3.79-2.682 4.645q0 0 0 0c-1.481.855-2.682.162-2.682-1.548s1.2-3.79 2.682-4.645c1.48-.855 2.682-.162 2.682 1.548m5.108-8.847c0 1.71-1.201 3.79-2.682 4.645q0 0 0 0c-1.481.855-2.682.162-2.682-1.548s1.2-3.79 2.682-4.645h0c1.48-.855 2.682-.162 2.682 1.548");
}

.o0_h56dwo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.578 13.036a4 4 0 0 1 2 3.464V34a4 4 0 0 1-2 3.464l-15.156 8.75a4 4 0 0 1-4 0l-15.155-8.75a4 4 0 0 1-2-3.464V16.5a4 4 0 0 1 2-3.464l15.155-8.75a4 4 0 0 1 4 0z");
}

</style>
