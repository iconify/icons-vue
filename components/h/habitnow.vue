<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="m_ensbcwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:habitnow" /></template>
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

.m_ensbcwl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.372 29.858a2.94 2.94 0 0 1-4.166 0l-5.43-5.43a1.66 1.66 0 0 0-2.381 0l-.893.892c-.67.67-.67 1.711 0 2.381l5.505 5.505a2.83 2.83 0 0 0 4.017 0l15.474-15.474c.67-.67.67-1.71 0-2.38l-.893-.893a1.66 1.66 0 0 0-2.38 0l-14.21 14.21");
}

</style>
