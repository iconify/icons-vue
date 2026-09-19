<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="byy7tjq3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:de-lijn" /></template>
<style>
.byy7tjq3e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.273 22.991h2.47l.871-4.94h-2.47zl-1.6-4.94h-2.47l-.871 4.94h2.47l.871-4.94m-8.282 4.94l.871-4.94h2.47l-.544 3.088c-.18 1.023-1.156 1.852-2.179 1.852h-1.853m-2.834-4.94l-.435 2.47h2.47l.436-2.47zm-1.86 4.94h-4.94l.871-4.94h2.47l-.87 4.94m30.506 2.47H19.19L16.186 42.5m6.523-37l-1.777 10.08H42.5");
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

</style>
