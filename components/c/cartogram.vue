<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hhey4c7bq"/><path class="diwshclgn"/><circle class="vx-qgob3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cartogram" /></template>
<style>
.diwshclgn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 33.557c2.622-4.46 6.701-8.908 6.679-13.382c-.013-2.49-2.72-5.838-6.679-5.934c-3.711-.09-6.6 2.977-6.536 6.757c.05 3.002 3.482 7.864 6.536 12.56");
}

.hhey4c7bq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4m4 22.906l-37 10.302M29.921 5.5l8.686 37m-28.13-5.178l1.087 5.178M5.5 24l27.164-6.816M11.69 5.5l3.992 15.945");
}

.vx-qgob3j {
  cx: 24px;
  cy: 20.4px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
