<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q1rw0j2co"/><path class="xribugbvb"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:adobe-capture" /></template>
<style>
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

.q1rw0j2co {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.657 26.964v.074A5.96 5.96 0 0 1 17.695 33h0a5.96 5.96 0 0 1-5.963-5.962v-6.075A5.96 5.96 0 0 1 17.695 15h0a5.96 5.96 0 0 1 5.962 5.963v.073M36.26 28.5c0 2.485-2 4.5-4.466 4.5h-1.568c-1.634 0-2.958-1.335-2.958-2.981c0-1.647 1.324-2.982 2.958-2.982h6.042");
}

.xribugbvb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.393 22.256c1.084-1.086 1.844-1.181 3.937-1.181c2.376 0 3.938 1.045 3.938 3.87V33");
}

</style>
