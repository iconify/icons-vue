<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lop5ofqta"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:centraal-beheer" /></template>
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

.lop5ofqta {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.34 12.093c-9.102 2.197-17.178 6.282-17.785 13.795c-.644 7.95 4.55 9.513 7.996 10.019m7.304-10.976c5.427-2.49 10.344-2.123 9.563 3.944c-.558 4.33-5.906 6.756-11.811 7.032l3.86-18.843");
}

</style>
