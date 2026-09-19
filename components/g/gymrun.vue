<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vvu66fbpb"/><ellipse transform="rotate(-7.83 14.436 29.269)" class="o1nvz-rwg"/><ellipse transform="rotate(-7.83 30.977 25.777)" class="pujipjbbx"/><path class="eswinkbgz"/><ellipse transform="rotate(-11.918 14.151 29.27)" class="yxf_p5bar"/><path class="yx9b9rbuf"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gymrun" /></template>
<style>
.eswinkbgz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.69 17.679c4.511 2.41 5.63 11.624 2.575 15.598m-14.56-5.315l9.544-2.104m6.489-1.43l2.538-.56M8.724 30.603l5.332-1.176");
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

.o1nvz-rwg {
  cx: 14.437px;
  cy: 29.269px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.745px;
  ry: 7.299px;
}

.pujipjbbx {
  cx: 30.977px;
  cy: 25.777px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.745px;
  ry: 7.299px;
}

.vvu66fbpb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.597 20.873c4.063 2.379 6.224 11.679 2.204 15.647");
}

.yx9b9rbuf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.519 25.654c.312 1.297.08 2.52-.519 2.74s-1.344-.644-1.667-1.938c-.323-1.293-.104-2.531.49-2.774s1.342.6 1.675 1.89M37.123 5.5l.066 6.897l-2.215-1.437l-1.696 1.37l-.067-6.83");
}

.yxf_p5bar {
  cx: 14.151px;
  cy: 29.269px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.155px;
  ry: 2.435px;
}

</style>
