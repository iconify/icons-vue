<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="qds7wmb4i"/><path class="pptuahb3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bouncer" /></template>
<style>
.pptuahb3u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.597 20.192a9.56 9.56 0 0 0-7.011 9.207V43.5h32.828V29.399a9.56 9.56 0 0 0-7.012-9.207m-15.185-8.154h3.898a.91.91 0 0 1 .912.912v1.549a2 2 0 0 1-2.001 2.001h-1.72a2 2 0 0 1-2.002-2.001V12.95a.91.91 0 0 1 .913-.912m7.668 0h3.899a.91.91 0 0 1 .912.912v1.549a2 2 0 0 1-2.002 2.001h-1.72a2 2 0 0 1-2.001-2.001V12.95a.91.91 0 0 1 .912-.912m-.912 1.905h-1.946");
}

.qds7wmb4i {
  cx: 24px;
  cy: 15.153px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 10.669px;
  ry: 10.653px;
}

</style>
