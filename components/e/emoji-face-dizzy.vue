<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="leoa6uwdy"/><circle class="el-z-nbbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-face-dizzy" /></template>
<style>
.el-z-nbbd {
  cx: 24.04px;
  cy: 31.038px;
  r: 4.223px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.leoa6uwdy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.612 20.984l-5.228-5.229M24.04 42.5c10.215 0 18.46-8.285 18.46-18.54c0-10.215-8.245-18.46-18.46-18.46C13.785 5.5 5.5 13.745 5.5 23.96c0 10.255 8.285 18.54 18.54 18.54m9.572-26.745l-5.228 5.229m-8.687 0l-5.229-5.229m5.229 0l-5.229 5.229");
}

</style>
