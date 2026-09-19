<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pf7spp0td"/><circle class="n65--4pyc"/><path class="il4l6b43e"/><path class="z7fs2kb4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bluetoothterminal" /></template>
<style>
.il4l6b43e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.4 14.4H29c2.5 0 4.4 2.5 4.4 5.7v4.1c0 3.1-2 5.7-4.4 5.7h-1.6c-2.5 0-4.4-2.5-4.4-5.7v-4.1c-.1-3.2 1.9-5.7 4.4-5.7");
}

.n65--4pyc {
  cx: 14.5px;
  cy: 33.4px;
  r: 1.6px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pf7spp0td {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.2 10.1h25.5a1.22 1.22 0 0 1 1.2 1.2v25.6a1.22 1.22 0 0 1-1.2 1.2H11.2a1.22 1.22 0 0 1-1.2-1.2V11.2a1.2 1.2 0 0 1 1.2-1.1");
}

.z7fs2kb4v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25 19.2l6 5.8l-2.7 2.6V17l2.6 2.5l-5.9 6M12.5 5.4V10m3.3-4.6V10M19 5.4V10m3.3-4.6V10m3.3-4.6V10m3.2-4.6V10m3.3-4.6V10m3.2-4.6V10M12.5 38v4.6m3.3-4.6v4.6M19 38v4.6m3.3-4.6v4.6m3.3-4.6v4.6m3.2-4.6v4.6m3.3-4.6v4.6m3.2-4.6v4.6M5.5 12.5H10m-4.5 3.3H10m-4.5 3.3H10m-4.5 3.3H10m-4.5 3.3H10m-4.5 3.2H10m-4.5 3.3H10m27.9-19.7h4.6m-4.6 3.3h4.6m-4.6 3.3h4.6m-4.6 3.3h4.6m-4.6 3.3h4.6m-4.6 3.2h4.6m-4.6 3.3h4.6m-37 3.4H10m27.9 0h4.6");
}

</style>
