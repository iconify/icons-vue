<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y6lactblt"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cdkeys" /></template>
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

.y6lactblt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.448 25.718v.043a3.474 3.474 0 1 1-6.948 0v-3.54a3.474 3.474 0 1 1 6.948 0v.043m2.688 6.971V18.747h2.36a4.59 4.59 0 0 1 4.588 4.589v1.31a4.59 4.59 0 0 1-4.588 4.59zm9.727-10.47v10.488m0-3.653l5.637-6.8m0 10.453l-4.318-5.244");
}

</style>
