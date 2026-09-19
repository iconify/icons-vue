<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zhnw7mp4m"/><circle class="cpk0fnbgt"/><circle class="yof2h0top"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:laos-lottery-result" /></template>
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

.yof2h0top {
  cx: 21.93px;
  cy: 22.289px;
  r: 13.176px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zhnw7mp4m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.295 16.982c2.327.515 3.795 2.785 3.291 5.09l-.925 4.24c-.504 2.305-2.783 3.746-5.111 3.23c-2.328-.514-3.796-2.785-3.293-5.09l.927-4.239c.504-2.305 2.783-3.746 5.11-3.231m2.883 2.189l-8.522 8.18m-7.42-11.465l3.545-1.008l-2.744 12.56");
}

</style>
