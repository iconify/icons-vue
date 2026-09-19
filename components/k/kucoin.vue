<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dlgw5zbbk"/><circle class="klynq8bxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kucoin" /></template>
<style>
.dlgw5zbbk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.425 7.257v33.164m33.155-9.772L28.305 42.925a1.954 1.954 0 0 1-2.77 0l-17.54-17.54a1.954 1.954 0 0 1 0-2.77l17.54-17.54a1.954 1.954 0 0 1 2.77 0L40.58 17.351");
}

.klynq8bxx {
  cx: 26.944px;
  cy: 24px;
  r: 2.611px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
