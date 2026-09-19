<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="bulzdab4q"/><ellipse class="iim2o_nnf"/><path class="syvmz3b1n"/><path class="vzrby1brl"/><path class="t2ob4-i5g"/><path class="clipnmb4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ensu" /></template>
<style>
.bulzdab4q {
  cx: 17.511px;
  cy: 29.792px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.716px;
  ry: 6.289px;
}

.clipnmb4p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.403 9.676c2.418-2.106 8.743-.306 6.284 5.06c4.884-1.237 7.042 3.22 4.45 6.253m-5.997-3.992c-1.168.36-1.52 1.258-1.52 1.258m-8.189-5.322c2.69 1.881 2.643 2.916 2.894 4.983m-6.707-3.102c-1.572 1.271-3.596 1.02-3.596 1.02");
}

.iim2o_nnf {
  cx: 30.838px;
  cy: 29.792px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.716px;
  ry: 6.289px;
}

.syvmz3b1n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 41.566c8.162 0 19 .134 19-11.774c0-12.243-12.61-11.875-19-11.875S5 17.549 5 29.792C5 41.7 15.838 41.566 24 41.566");
}

.t2ob4-i5g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.058 13.4c-.603-6.137 5.553-6.873 7.46-2.692c.955-5.452 5.58-4.85 7.755-2.794c2.717 2.57.665 6.36-1.289 7.933");
}

.vzrby1brl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.76 21.967c-2.191-3.431-.686-7.412 2.693-8.315s5.336.59 6.531 4.527");
}

</style>
