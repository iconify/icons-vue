<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="kof-7sarc"/><path class="vwmzg0wfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:atb-personal" /></template>
<style>
.kof-7sarc {
  width: 39px;
  height: 26px;
  x: 4.5px;
  y: 11px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.vwmzg0wfz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.462 18.65h8.343m-4.171 10.7v-10.7M32.22 24a2.675 2.675 0 1 1 0 5.35h-4.414v-10.7h4.413a2.675 2.675 0 1 1 0 5.35m0 0h-4.414m-8.785 1.806h-4.74m-1.174 3.544l3.544-10.7l3.545 10.7");
}

</style>
