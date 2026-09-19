<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect transform="rotate(45 25.243 24)" class="v-axu8btf"/><path class="j41oe0zuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:drowser" /></template>
<style>
.j41oe0zuu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.03 30.787L18.456 17.213");
}

.v-axu8btf {
  width: 19.198px;
  height: 44.407px;
  x: 15.644px;
  y: 1.797px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 9.599px;
}

</style>
