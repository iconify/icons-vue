<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><circle class="s1m9pwbta"/><path class="ybdc0jgsb"/><circle class="i7woh20-z"/><path class="xe-in4bby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:iliad" /></template>
<style>
.i7woh20-z {
  cx: 20.427px;
  cy: 19.768px;
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

.s1m9pwbta {
  cx: 13.34px;
  cy: 19.768px;
  r: 0.75px;
  fill: currentColor;
}

.xe-in4bby {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.427 22.709v6.363m-4.25-9.604v8.404a1.2 1.2 0 0 0 1.2 1.2h.36m10.211-2.401a2.401 2.401 0 1 1-4.802 0v-1.56a2.401 2.401 0 1 1 4.802 0m0 3.961v-6.363M35.5 25.11a2.401 2.401 0 1 0-4.802 0v1.561a2.401 2.401 0 1 0 4.802 0m0 2.401v-9.604");
}

.ybdc0jgsb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.34 22.709v6.363");
}

</style>
