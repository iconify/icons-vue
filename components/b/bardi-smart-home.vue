<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="sla_6-4gq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bardi-smart-home" /></template>
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

.sla_6-4gq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.5 20.262v7.476m-13.634 0v-7.476h2.447c1.384 0 2.506 1.124 2.506 2.51s-1.122 2.512-2.506 2.512h-2.447m2.447-.001l2.448 2.453m1.91.002v-7.476h1.682a3.27 3.27 0 0 1 3.271 3.27v.935a3.27 3.27 0 0 1-3.27 3.271zM13.584 24a1.87 1.87 0 1 1 0 3.738H10.5v-7.476h3.084a1.87 1.87 0 1 1 0 3.738m0 0H10.5m10.512 1.262h-3.313m-.819 2.476l2.476-7.476l2.477 7.476");
}

</style>
