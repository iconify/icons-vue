<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="xqjbduv-t"/><path class="uh_9286ik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:exteragram-google" /></template>
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

.uh_9286ik {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.02 27.48A12.94 12.94 0 0 1 26.06 26c1.32 0 2.6.2 3.8.56M16.6 25.11c5.14-1.54 9.49-4.92 12.28-9.37");
}

.xqjbduv-t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.345 27.778c1.777 1.78 3.015 4.217 3.84 6.359c.547 1.424 2.569 1.396 3.068-.046l5.865-16.928c.46-1.327-.811-2.6-2.139-2.142L14.043 20.86c-1.443.497-1.474 2.519-.051 3.069c2.14.827 4.576 2.069 6.353 3.849");
}

</style>
