<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kg4ghsblu"/><path class="l8nllhb9y"/><path class="elnym0bll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ivpn" /></template>
<style>
.elnym0bll {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.147 22.955c.288.834.438.717 3.258.717h1.148m13.671 3.669c-.288.834-.438.717-3.258.717h-.733m5.62-5.103c-.288.834-.438.717-3.258.717h-1.148");
}

.kg4ghsblu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 43.5c9.043-3.117 15.489-10.363 16.5-19.589c.28-4.005.257-8.025-.071-12.027a2.54 2.54 0 0 0-2.468-2.366c-4.091-.126-8.846-.808-12.52-4.427a2.05 2.05 0 0 0-2.881 0c-3.675 3.619-8.43 4.301-12.52 4.427a2.54 2.54 0 0 0-2.468 2.366A79.4 79.4 0 0 0 7.5 23.911C8.512 33.137 14.957 40.383 24 43.5");
}

.l8nllhb9y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12 17.321s.185.491.448 1.151c.107.27.367.448.657.45c1.37.004 3.823.018 6.179-.151L24 30.679l4.716-11.908c2.357.169 4.81.155 6.18.15c.29 0 .55-.18.657-.449c.262-.66.447-1.15.447-1.15M15.776 27.341c.288.834.438.717 3.258.717h.733");
}

</style>
