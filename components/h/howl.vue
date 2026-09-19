<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="fknrpjbyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:howl" /></template>
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

.fknrpjbyv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.73 25.253s4.693 1.177 6.52 0c5.522-3.555.73-17.554 8.153-17.935c12.621-.533-1.573 34.217 12.487 34.239c7.042-.381 3.54-13.11 8.709-16.304c1.85-1.143 6.522 0 6.522 0");
}

</style>
