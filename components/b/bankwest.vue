<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="yeuuv9bwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bankwest" /></template>
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

.yeuuv9bwe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14 21.438l1.768-1.812c.976-1 .976-2.622 0-3.623c-.977-1-2.56-1-3.536 0a2.607 2.607 0 0 0 0 3.623l8.536 8.747a2.61 2.61 0 0 1 0 3.624c-.977 1-2.56 1-3.536 0a2.607 2.607 0 0 1 0-3.623l8.536-8.747a2.61 2.61 0 0 0 0-3.624c-.977-1-2.56-1-3.536 0a2.607 2.607 0 0 0 0 3.623l8.536 8.747a2.61 2.61 0 0 1 0 3.624c-.977 1-2.56 1-3.536 0a2.607 2.607 0 0 1 0-3.623l8.536-8.747a2.61 2.61 0 0 0 0-3.624c-.977-1-2.56-1-3.536 0a2.607 2.607 0 0 0 0 3.623L34 21.439");
}

</style>
