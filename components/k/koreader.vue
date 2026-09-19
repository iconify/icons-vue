<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mij5gfbmu"/><path class="f3h-ggl2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:koreader" /></template>
<style>
.f3h-ggl2y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.3 30l-4.94-6l4.94-5.96M19.36 24h-1.51m8.68 2a4 4 0 0 0 7.95 0v-4a4 4 0 1 0-7.95 0Z");
}

.mij5gfbmu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.4 6.45v35.1a2 2 0 0 0 1.95 2h2.38V4.5h-2.38A2 2 0 0 0 8.4 6.45m4.33-1.95v39h24.92a2 2 0 0 0 2-2V6.45a2 2 0 0 0-2-1.95ZM17.85 18v12");
}

</style>
