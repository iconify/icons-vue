<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l0e2m3e0l"/><path class="hz4qczbxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:blocket" /></template>
<style>
.hz4qczbxu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18 26.1a6 6 0 0 1 12 0V30a6 6 0 0 1-12 0m0 6V12");
}

.l0e2m3e0l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.5 4.5h-27a2 2 0 0 0-2 2v35a2 2 0 0 0 2 2h27a2 2 0 0 0 2-2v-35a2 2 0 0 0-2-2M12 7V3m6 4V3m6 4V3m6 4V3m6 4V3");
}

</style>
