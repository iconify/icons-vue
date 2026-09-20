<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="krur5g8vt"/><circle class="cpk0fnbgt"/><path class="x4k45eaxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lappli-m" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.krur5g8vt {
  cx: 24px;
  cy: 24px;
  r: 17.902px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.x4k45eaxj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m38.846 13.997l2.976-2.024m-1.318 5.093l3.312-1.408m-3.173 14.936l3.312 1.408m-6.507 3.816l2.767 2.3M24 41.902V45.5M9.428 39.808l2.416-2.665m-4.95-.12l2.863-2.179M3.354 30l3.43-1.093M19.124 3.06l.952 3.474m12.222 1.603l1.691-3.175M17.344 30.64V17.345L24 30.656l6.656-13.292v13.292");
}

</style>
