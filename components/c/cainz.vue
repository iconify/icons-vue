<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="r7wsm4bxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cainz" /></template>
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

.r7wsm4bxf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 19.442v5.797m2.262 0v-5.797l3.964 5.797v-5.797m2.262 0h3.964l-3.964 5.797h3.964m-20.94-1.944v.024c0 1.06-.887 1.92-1.982 1.92s-1.982-.86-1.982-1.92v-1.957c0-1.06.888-1.92 1.982-1.92s1.982.86 1.982 1.92v.024m2.262 3.853l1.982-5.797l1.982 5.797M8.797 28.558c7.63-.887 19.731-.98 28.291-.216");
}

</style>
