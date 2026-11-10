<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="gkbzx0-9v"/><path class="xf0sukk-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:anyapk" /></template>
<style>
.gkbzx0-9v {
  width: 23px;
  height: 39px;
  x: 12.5px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

.xf0sukk-h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.5 8h23m0 32h-23m7.118-15.401l2.522 2.522l6.242-6.243");
}

</style>
