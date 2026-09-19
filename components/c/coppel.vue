<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dea_308ib"/><path class="ysmy1pbbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:coppel" /></template>
<style>
.dea_308ib {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.54 24c0 1.958-1.576 3.545-3.52 3.545S4.5 25.958 4.5 24h0c0-1.958 1.576-3.545 3.52-3.545h0c1.944 0 3.52 1.587 3.52 3.545");
}

.ysmy1pbbg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.72 20.43c0 1.957-1.576 3.544-3.52 3.544s-3.52-1.587-3.52-3.545h0c0-1.957 1.576-3.544 3.52-3.544s3.52 1.587 3.52 3.544zm0 7.14c0 1.958-1.576 3.545-3.52 3.545h0c-1.944 0-3.52-1.587-3.52-3.544s1.576-3.545 3.52-3.545h0c1.944 0 3.52 1.587 3.52 3.545zM14.705 24H43.5m-5.778 0v6.07M42.037 24v6.07m-4.316-2.529h4.318");
}

</style>
