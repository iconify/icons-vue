<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="trs9ulb0b"/><path class="d43aqcbez"/><path class="g0elml8ao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:atmospherelogger" /></template>
<style>
.d43aqcbez {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 42.5h-29c-2.2 0-4-1.8-4-4v-29c0-2.2 1.8-4 4-4h29c2.2 0 4 1.8 4 4v29c0 2.2-1.8 4-4 4m-25.6-37");
}

.g0elml8ao {
  fill: none;
  stroke: currentColor;
  stroke-dasharray: 0 0 0 3.7;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.9 9.2v31.4m7.4-31.4v31.4m7.4-31.4v31.4m7.4-31.4v31.4m3.7-27.7H7.4m31.4 7.4H7.4m31.4 7.4H7.3m31.5 7.4H7.3");
}

.trs9ulb0b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 21.8c3.8-2.1 2.2-5.9 7.4-6.9c3.7-.7 5.4 1.5 6 3.6c3.8 12.9 9.5 11.3 13.7 8c2.5-2 5.7-.7 6.4 3.2c.8 4.3 2.8 4.1 3.4 4.3");
}

</style>
