<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tm4n9cb_a"/><circle class="j515-c03w"/><path class="v1__dmb2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ir-remote" /></template>
<style>
.j515-c03w {
  cx: 17.989px;
  cy: 24.539px;
  r: 1.474px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tm4n9cb_a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.63 43.5V22.844a1.47 1.47 0 0 1 1.475-1.474h15.653a1.47 1.47 0 0 1 1.474 1.474V43.5z");
}

.v1__dmb2j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.994 14.86c-1.73-2.72-8.568-5.043-12.005 0m16.379-5.581c-3.915-4.619-13.824-7.915-20.736 0");
}

</style>
