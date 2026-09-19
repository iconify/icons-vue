<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pze_d3vji"/><ellipse transform="rotate(-15.345 11.853 25.081)" class="y965knb4m"/><ellipse transform="rotate(-7.22 18.689 16.348)" class="f39cpvbip"/><ellipse transform="rotate(-74.655 36.147 25.081)" class="duh56wbxh"/><ellipse transform="rotate(-82.78 29.311 16.348)" class="s1k3ll6xs"/><path class="qgybmk8tt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:amarok" /></template>
<style>
.duh56wbxh {
  cx: 36.147px;
  cy: 25.081px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.36px;
  ry: 3.679px;
}

.f39cpvbip {
  cx: 18.689px;
  cy: 16.348px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.856px;
  ry: 5.869px;
}

.pze_d3vji {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.25 19.046c.06-1.245-.448-2.824-1.683-4.451l-1.036 3.378c.998.198 1.75.54 2.72 1.073Zm-7.706-9.862a12.6 12.6 0 0 0-2.935-1.131l1.47-3.553c1.105 1.696 1.457 3.262 1.465 4.684M7.75 19.046c-.06-1.245.448-2.824 1.683-4.451l1.036 3.378c-.998.198-1.75.54-2.72 1.073m7.707-9.862c.776-.42 1.757-.835 2.935-1.131L16.921 4.5c-1.105 1.696-1.456 3.262-1.465 4.684");
}

.qgybmk8tt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.09 43.27c3.753.803 4.33-.718 4.822-1.178c1.053-.984 1.646-3.312 1.185-5.764c-.445-2.367-4.358-5.216-5.521-7.136c-1.833-3.026-1.94-5.741-6.576-5.876c-4.637.134-4.744 2.85-6.576 5.876c-1.163 1.92-5.077 4.77-5.522 7.136c-.46 2.452.132 4.78 1.186 5.764c.492.46 1.068 1.981 4.82 1.178c1.623-.347 3.635-1.98 6.092-1.886c2.456-.093 4.469 1.539 6.09 1.886");
}

.s1k3ll6xs {
  cx: 29.311px;
  cy: 16.348px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.869px;
  ry: 3.856px;
}

.y965knb4m {
  cx: 11.853px;
  cy: 25.081px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.679px;
  ry: 5.36px;
}

</style>
