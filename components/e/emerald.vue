<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s3dzcxa_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emerald" /></template>
<style>
.s3dzcxa_w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.11 5.5H14.89L5.5 14.88v18.23l9.39 9.39h18.22l9.39-9.39V14.88Z");
}

</style>
