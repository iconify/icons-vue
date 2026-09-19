<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pixdlvjro"/><path class="mbhvrx5dc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bazaar" /></template>
<style>
.mbhvrx5dc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.002 5.5c-3.793 0-5.811 3.63-8.017 9.953c-3.81.207-6.608.776-9.92 2.35C7.235 29.183 9.858 42.5 24 42.5s16.764-13.316 17.934-24.697c-3.312-1.574-6.108-2.143-9.918-2.35C29.814 9.131 27.795 5.5 24.002 5.5");
}

.pixdlvjro {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.017 15.453c-1.337-.014-4.115-.12-8.015-.12c-4.315 0-6.68.105-8.017.12");
}

</style>
