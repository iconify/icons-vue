<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eahclry3m"/><path class="op-oerd7u"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:boost-mobile" /></template>
<style>
.eahclry3m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.618 22.71l-.254-.253a2.744 2.744 0 1 0 0 3.881l3.881-3.88a2.744 2.744 0 1 1 0 3.88l-.253-.253m6.846.595c.378.317.787.462 1.703.462h.465a1.37 1.37 0 0 0 1.37-1.372h0a1.37 1.37 0 0 0-1.37-1.372h-.93a1.37 1.37 0 0 1-1.368-1.372h0a1.37 1.37 0 0 1 1.369-1.372h6.097");
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

.op-oerd7u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.154 19.945v6.162c0 .572.463 1.035 1.035 1.035h.311m-29-3.417a2.07 2.07 0 0 1 2.071-2.071h0a2.07 2.07 0 0 1 2.071 2.07v1.347a2.07 2.07 0 0 1-2.07 2.071h0a2.07 2.07 0 0 1-2.072-2.07m0-.001v-6.213");
}

</style>
