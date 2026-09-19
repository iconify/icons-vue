<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tykk0ub4m"/><rect class="uhx3m_1tm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:irplus" /></template>
<style>
.tykk0ub4m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.8 8.5H16m-3.2 4.8H16m-3.2 4.8H16m3.2-9.6h3.2m-3.2 4.8h3.2m-3.2 4.8h3.2m3.2-9.6h3.2m-3.2 4.8h3.2m-3.2 4.8h3.2M32 8.5h3.2M32 13.3h3.2M32 18.1h3.2M12.8 25H16m-3.2 4.9H16m-3.2 4.8H16m-3.2 4.8H16M19.2 25h3.2m-3.2 4.9h3.2m-3.2 4.8h3.2m-3.2 4.8h3.2M25.6 25h3.2m-3.2 4.9h3.2m-3.2 4.8h3.2m-3.2 4.8h3.2M32 25h3.2M32 29.9h3.2M32 34.7h3.2M32 39.5h3.2");
}

.uhx3m_1tm {
  width: 31px;
  height: 39px;
  x: 8.5px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
