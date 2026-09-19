<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="ubwvu5b4t"/><path class="vqgm9rbnn"/><path class="gouvtj5gz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:huawei-ai-voice" /></template>
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

.gouvtj5gz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.117 15.022c2.697 2.222 6.149 4.02 9.946 5.408m.797 1.343c-4.7 1.18-9.313 2.585-11.566-2.743");
}

.ubwvu5b4t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.132 8.47c1.9-1.619 4.198 1.358 4.88 4.813c1.066 5.393-7.665 24.092-9.764 19.208");
}

.vqgm9rbnn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.3 28.693C24 24 34.844 37.989 40.328 37.989M28.482 2.972C18.231 14.72 21.495 30.236 45.333 26.673");
}

</style>
