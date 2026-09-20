<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="rmvc906rr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:beebom" /></template>
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

.rmvc906rr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.83 25.342a3.835 3.835 0 1 1 7.67 0v2.493a3.835 3.835 0 1 1-7.67 0m-.001 3.836V16.329m-7 7.671a3.835 3.835 0 1 1 0 7.67H13.5V16.33h6.328a3.835 3.835 0 1 1 0 7.67m0 0H13.5");
}

</style>
