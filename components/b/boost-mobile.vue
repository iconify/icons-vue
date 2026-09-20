<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hedi8dp7m"/><path class="tz_yttprh"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:boost-mobile" /></template>
<style>
.hedi8dp7m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.618 22.71l-.254-.253a2.744 2.744 0 1 0 0 3.881l3.881-3.88a2.744 2.744 0 1 1 0 3.88l-.253-.253m6.846.595c.378.317.787.462 1.703.462h.465a1.37 1.37 0 0 0 1.37-1.372a1.37 1.37 0 0 0-1.37-1.372h-.93a1.37 1.37 0 0 1-1.368-1.372a1.37 1.37 0 0 1 1.369-1.372h6.097");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.tz_yttprh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.154 19.945v6.162c0 .572.463 1.035 1.035 1.035h.311m-29-3.417a2.071 2.071 0 0 1 4.142 0v1.346a2.071 2.071 0 0 1-4.142 0m0 0v-6.213");
}

</style>
