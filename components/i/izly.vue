<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="dl2bdvbbj"/><path class="w9lwm3qoh"/><path class="spllx3tti"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:izly" /></template>
<style>
.dl2bdvbbj {
  cx: 15.256px;
  cy: 21.654px;
  r: 0.75px;
  fill: currentColor;
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

.spllx3tti {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.914 24.321v3.593a2.18 2.18 0 0 1-2.177 2.178h0a2.18 2.18 0 0 1-2.178-2.178v-3.593m-1.241-4.792c.403.509.642 1.154.642 1.853m.943-3.354a5.15 5.15 0 0 1 1.235 3.354h0q0 .133-.007.265m.323-5.154a7.33 7.33 0 0 1 1.861 4.889h0q0 .254-.016.504m-.287-6.917a9.5 9.5 0 0 1 2.482 6.413h0q0 .39-.033.777");
}

.w9lwm3qoh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.256 24.321v5.77m8.71-8.709v7.62c0 .602.488 1.09 1.089 1.09h.327m-7.948-5.771h4.355l-4.355 5.77h4.355m10.125-2.177v2.94a2.18 2.18 0 0 1-2.177 2.177h0c-.578 0-1.132-.23-1.54-.638");
}

</style>
