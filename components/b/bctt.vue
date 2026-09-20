<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="o9l0kkbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bctt" /></template>
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

.o9l0kkbta {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.5 25.115a3.041 3.041 0 1 1 6.083 0v1.976a3.041 3.041 0 1 1-6.083 0m0 2.925V17.851m13.588 10.754c-.494.923-1.423 1.544-2.487 1.544c-1.582 0-2.864-1.373-2.864-3.067V25.09c0-1.694 1.282-3.067 2.864-3.067c1.062 0 1.99.62 2.484 1.54m3.487-3.804v8.894c0 .826.777 1.495 1.736 1.495h.521m-4.08-7.923h3.646m3.848-2.607v8.894c0 .826.777 1.495 1.736 1.495h.521m-4.08-7.923h3.646");
}

</style>
