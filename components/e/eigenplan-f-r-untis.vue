<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m-7c2636w"/><path class="gtywr3byd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:eigenplan-f-r-untis" /></template>
<style>
.gtywr3byd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.311 21.494v11.19l-11.826 6.828l-13.03-7.523V21.205");
}

.m-7c2636w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.5 17.997l18.696 10.074l18.21-9.886l-18.21-9.697zm36.906.188l.094 15.11");
}

</style>
