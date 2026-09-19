<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zos7-9d6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gsmarena" /></template>
<style>
.zos7-9d6f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.823 22.28L21.591 4.5h16.705v27.947l-10.373-3.839l-.261-14.209l-8.094 11.118Zm5.037 11.053L38.297 43.5H9.704Z");
}

</style>
