<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="ib6klufup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kmitl-uapp" /></template>
<style>
.ib6klufup {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.082 28.364L10.591 24M9.5 25.309l4.582-5.673m-4.582 0v8.728m20.254 0v-8.728m-2.836 0h5.673M14.98 26.929l1.262-7.292l2.871 8.726l2.873-8.726l1.491 8.726m1.984-8.726v8.726m8.675-8.726v8.726H38.5");
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
