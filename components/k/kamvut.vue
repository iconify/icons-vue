<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="but1twbmq"/><circle class="rq7ktlboa"/><circle class="tmqmg9cny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kamvut" /></template>
<style>
.but1twbmq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 10.403a37 37 0 0 1 37 0L24 42.554z");
}

.rq7ktlboa {
  cx: 18.259px;
  cy: 12.954px;
  r: 3.828px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tmqmg9cny {
  cx: 24px;
  cy: 24.054px;
  r: 3.828px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
