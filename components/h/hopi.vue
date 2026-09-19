<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="s0w80p_ef"/><circle class="j-6zrfssd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hopi" /></template>
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

.j-6zrfssd {
  cx: 37.439px;
  cy: 16.163px;
  r: 0.75px;
  fill: currentColor;
}

.s0w80p_ef {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.811 16.164v12.433m-.001-5.219c0-1.688 1.382-3.07 3.07-3.07s3.07 1.382 3.07 3.07v5.065m12.143-2.916c0 1.688 1.381 3.07 3.07 3.07s3.07-1.382 3.07-3.07V23.53c0-1.688-1.382-3.07-3.07-3.07s-3.07 1.382-3.07 3.07m0-3.222v12.279m-9.145-7.214c0 1.688 1.382 3.07 3.07 3.07s3.07-1.382 3.07-3.07v-1.996c0-1.688-1.382-3.07-3.07-3.07s-3.07 1.382-3.07 3.07zm18.491-5.065v8.288");
}

</style>
