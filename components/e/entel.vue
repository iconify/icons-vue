<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oz0h5qbaf"/><path class="cy-d7_i0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:entel" /></template>
<style>
.cy-d7_i0l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 42.5h-29a4 4 0 0 1-4-4v-29a4 4 0 0 1 4-4h29a4 4 0 0 1 4 4v29a4 4 0 0 1-4 4");
}

.oz0h5qbaf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.629 30.077c-1.105 2.21-3.684 3.684-6.262 3.684c-4.052 0-7.367-3.315-7.367-7.367v-4.788c0-4.052 3.315-7.367 7.367-7.367s7.367 3.315 7.367 7.367v2.578H13M31.513 16.6C33.647 18.39 35 21.043 35 24s-1.353 5.61-3.487 7.4");
}

</style>
