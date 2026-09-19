<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uqb613bhn"/><circle class="knrby8etb"/><path class="godqw3bzm"/><path class="h__fy2cwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:casio-gshock" /></template>
<style>
.godqw3bzm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.637 28.45v-8.9c0-.96.382-1.881 1.061-2.56l6.292-6.292c.68-.68 1.6-1.061 2.56-1.061h8.9c.96 0 1.88.381 2.56 1.06l6.292 6.293a3.62 3.62 0 0 1 1.06 2.56v8.899a3.62 3.62 0 0 1-1.06 2.56l-6.292 6.292c-.68.68-1.6 1.061-2.56 1.061h-8.9c-.96 0-1.88-.381-2.56-1.06l-6.292-6.293a3.62 3.62 0 0 1-1.06-2.56");
}

.h__fy2cwg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.863 21.156c1.93-2.828 1.412-3.572.94-3.645c-2.771-.434-11.028 12.754-8.726 12.982c1.845.184 4.552-3.402 6.381-5.289l-2.688.002h6.554");
}

.knrby8etb {
  cx: 24px;
  cy: 24px;
  r: 11.48px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.uqb613bhn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.332 12.02l-1.21-5.241A2.94 2.94 0 0 0 28.257 4.5h-8.513a2.94 2.94 0 0 0-2.865 2.279l-1.21 5.241m-.001 23.96l1.21 5.241a2.94 2.94 0 0 0 2.865 2.28h8.513a2.94 2.94 0 0 0 2.865-2.28l1.21-5.241");
}

</style>
