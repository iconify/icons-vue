<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="o9ixm4bcs"/><path class="j757l3bqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:karui" /></template>
<style>
.j757l3bqa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.766 9.767v28.242M30.04 24.047v13.962M17.766 24.047h24.637");
}

.o9ixm4bcs {
  width: 37px;
  height: 28.241px;
  x: 5.403px;
  y: 9.767px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
