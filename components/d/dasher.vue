<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kg0y7n6ik"/><rect class="tk1y-acic"/><path class="s4_gmnovw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dasher" /></template>
<style>
.kg0y7n6ik {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.224 31.315h5.278a4.113 4.113 0 0 0 4.113-4.113a4.113 4.113 0 0 0-4.114-4.114H15.386");
}

.s4_gmnovw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.542 10.903V7.268A2.77 2.77 0 0 0 27.774 4.5h-7.548a2.77 2.77 0 0 0-2.768 2.768v3.635");
}

.tk1y-acic {
  width: 29.99px;
  height: 32.597px;
  x: 9.005px;
  y: 10.903px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.384px;
}

</style>
