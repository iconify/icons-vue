<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tbooxtbvh"/><path class="zy31znbkx"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:faire-brand" /></template>
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

.tbooxtbvh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.789 11.5h20.038l2.384 5.928c-3.93-3.286-7.925-5.928-9.793-5.928m-1.933 12.36a5.47 5.47 0 0 1 5.47 5.472V18.389a5.47 5.47 0 0 1-5.47 5.471");
}

.zy31znbkx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.789 11.5a3.37 3.37 0 0 1 3.37 3.37v18.26a3.37 3.37 0 0 1-3.37 3.37h10.696a3.37 3.37 0 0 1-3.37-3.37V14.87c0-1.861.349-3.37 2.21-3.37m1.16 12.36h-3.37");
}

</style>
