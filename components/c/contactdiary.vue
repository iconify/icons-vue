<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="nmshnxbeg"/><path class="ed9yw-btx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:contactdiary" /></template>
<style>
.ed9yw-btx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.41 7.029V4.5m19.18 2.529V4.5M7.5 16.947h33m-25.482 8.937h18.834m-18.834 7.57h12.989");
}

.nmshnxbeg {
  width: 33px;
  height: 36.471px;
  x: 7.5px;
  y: 7.029px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
