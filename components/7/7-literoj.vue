<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fv6g-_b3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:7-literoj" /></template>
<style>
.fv6g-_b3x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 9.189h19.622L11.83 38.811m30.67 0H22.878L36.17 9.189m-6.065 13.516H9.804");
}

</style>
