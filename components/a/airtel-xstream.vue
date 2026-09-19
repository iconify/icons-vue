<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x699ewbqd"/><path class="seujh6qpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:airtel-xstream" /></template>
<style>
.seujh6qpm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.017 22.189l2.968 2.968l-3.08 3.08l-3.036-3.036Z");
}

.x699ewbqd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.112 42.5h-5.725L19.87 27.985l-5.71 5.708H8.585l8.563-8.562L5.71 13.695h5.766l8.542 8.54L36.756 5.5h5.534L22.695 25.093Z");
}

</style>
