<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="tsa4-2-ul"/><path class="h-h5b9dfo"/><circle class="fd85t5b_y"/><path class="eq9z-9bbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:amdroid" /></template>
<style>
.eq9z-9bbu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.78 7.26a5 5 0 1 0-7.12 7Zm-7.06-.07l-.62-.62m4.12 4.18l1.1 1.12m22.9-4.61a5 5 0 1 1 7.12 7Zm7.06-.07l.62-.62m-4.12 4.18l-1.1 1.12m-.34 25.68a17.9 17.9 0 0 0-7.81-30.33V6.14a1.65 1.65 0 0 0-1.64-1.64h-5.78a1.65 1.65 0 0 0-1.64 1.64v1.08a17.9 17.9 0 0 0-7.81 30.33l-1.89 3.26a1.79 1.79 0 1 0 3.11 1.79l1.64-2.84a17.82 17.82 0 0 0 19 0l1.64 2.84a1.79 1.79 0 0 0 3.11-1.79Z");
}

.fd85t5b_y {
  cx: 24px;
  cy: 24.56px;
  r: 14.35px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.h-h5b9dfo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 22.25v-9.09m-1.5 12.89l-6.55 6.56");
}

.tsa4-2-ul {
  cx: 24px;
  cy: 24.49px;
  r: 2.23px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
