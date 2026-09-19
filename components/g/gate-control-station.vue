<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect transform="rotate(30 23.744 23.852)" class="m-j3y5_0m"/><path class="bct7m-bva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gate-control-station" /></template>
<style>
.bct7m-bva {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.181 28.284l-5.298-3.06m-10.49-6.056L14.7 16.459m18.726 14.865l-5.299-3.059m-10.49-6.056l-4.693-2.71M31.67 34.365l-5.298-3.059m-10.49-6.057l-4.693-2.709m25.748 2.703l-5.299-3.059m-10.49-6.057l-4.693-2.709m19.954 1.371h-7.091l-3.545-6.141H11.591L4.5 20.93l7.091 12.281h7.091l3.545 6.141h14.182L43.5 27.07z");
}

.m-j3y5_0m {
  width: 12px;
  height: 16px;
  x: 17.744px;
  y: 15.852px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.101px;
  ry: 1.101px;
}

</style>
