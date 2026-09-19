<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="vzexv7bas"/><circle class="cpk0fnbgt"/><path class="vjwvcbcev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:alarmio" /></template>
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

.vjwvcbcev {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.77 14.01l1.68-2.9m2.54 7.12l2.91-1.67M35.54 24h3.35m-9.12 9.99l1.67 2.91M24 35.54l-.01 3.35m-5.76-4.9l-1.68 2.9M14 29.76l-2.9 1.68m1.36-7.45H9.11m4.9-5.77l-2.9-1.67M18.24 14l-1.68-2.9M24 6.91v13.78m13.21 10.67L26.88 25.6");
}

.vzexv7bas {
  cx: 24px;
  cy: 23.99px;
  r: 3.3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
