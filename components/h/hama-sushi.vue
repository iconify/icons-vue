<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="cdxoss1ab"/><path class="tp4mtbb9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hama-sushi" /></template>
<style>
.cdxoss1ab {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.906 14.645c-4.339 4.314-4.027 32.723 2.575 13.805m1.986-7.209c-1.907-1.901 7.104-3.804 12.804-3.957");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.tp4mtbb9q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.981 12.99c-2.284 3.945 2.716 20.667-3.98 20.543c-4.323-.08-5.707-4.039-2.391-5.518c2.591-1.156 7.743-1.656 12.372 6.962");
}

</style>
